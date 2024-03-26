<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-dark text-white">
      <q-toolbar>
        <q-btn
          flat
          dense
          round
          icon="menu"
          aria-label="Menu"
          @click="toggleLeftDrawer"
        />

        <q-toolbar-title>
          Agustín Danel Vissani
          <q-avatar>
            <img
              src="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
            />
          </q-avatar>
        </q-toolbar-title>

        <q-btn @click="downloadCV">Download CV</q-btn>
      </q-toolbar>
    </q-header>

    <q-drawer
      v-model="leftDrawerOpen"
      show-if-above
      bordered
      class="bg-dark text-white"
    >
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
      <ChatComponent2 />
      <ProjectComponent />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";
import EssentialLink from "components/EssentialLink.vue";

import ChatComponent from "components/ChatComponent.vue";
import ToolsItComponent from "components/ToolsItComponent.vue";
import ChatComponent2 from "components/ChatComponent2.vue";
import ProjectComponent from "components/ProjectComponent.vue";

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
    ChatComponent2,
    ProjectComponent,
  },

  setup() {
    const leftDrawerOpen = ref(false);

    const toggleLeftDrawer = () => {
      leftDrawerOpen.value = !leftDrawerOpen.value;
    };

    const downloadCV = () => {
      const pdfURL =
        "https://drive.google.com/file/d/1QVflbNpwr-tZFo0D8HTc3ivVY1S0Bqk5/view?usp=drive_link";
      window.open(pdfURL, "_blank");
    };

    return {
      essentialLinks: linksList,
      leftDrawerOpen,
      toggleLeftDrawer,
      downloadCV,
    };
  },
});
</script>

<style>
body {
  background-color: black;
}
</style>
