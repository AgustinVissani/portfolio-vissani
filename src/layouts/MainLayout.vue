<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated  class="bg-dark text-white">
      <q-toolbar>
        <q-btn
          flat
          dense
          round
          icon="menu"
          aria-label="Menu"
          @click="toggleLeftDrawer"
        />

        <q-toolbar-title> Agustín Danel Vissani
          <q-avatar>
          <img src="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no" />
        </q-avatar>
  
        </q-toolbar-title>

        <div>Portfolio</div>
      </q-toolbar>
    </q-header>

    <q-drawer v-model="leftDrawerOpen" show-if-above bordered class="bg-dark text-white">
      <q-list>
        <q-item-label header> Links </q-item-label>

        <EssentialLink
          v-for="link in essentialLinks"
          :key="link.title"
          v-bind="link"
        />
      </q-list>
    </q-drawer>

    <q-page-container>
      <ChatComponent />
      <ToolsItComponent />
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";
import EssentialLink from "components/EssentialLink.vue";

import ChatComponent from "components/ChatComponent.vue"; 
import ToolsItComponent from "components/ToolsItComponent.vue"; 

const linksList = [
  {
    title: "Github",
    caption: "github.com/AgustinVissani",
    icon: "code",
    link: "https://github.com/AgustinVissani",
  },
];

export default defineComponent({
  name: "MainLayout",

  components: {
    EssentialLink,    
    ChatComponent,    
    ToolsItComponent,
  },

  setup() {
    const leftDrawerOpen = ref(false);

    return {
      essentialLinks: linksList,
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value;
      },
    };
  },
});
</script>

<style>
body {
  background-color: black;
}
</style>