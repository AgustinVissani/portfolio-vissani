<template>
  <div class="q-pa-md q-gutter-sm">
    <div v-for="(project, index) in projects" :key="index">
      <q-banner rounded :class="$q.dark.isActive ? 'bg-grey-2' : 'bg-black'">
        <h4 class="title">{{ project.title }}</h4>
        <q-label class="description">{{ project.description }}</q-label>
        <template v-slot:action>
          <a :href="project.url" target="_blank" class="button-link">VISIT</a>
        </template>
        <template v-slot:avatar>
          <img :src="project.imageUrl" style="width: 200px; height: 130px" />
        </template>
        <q-badge class="q-ma-xs blue">{{ project.badgeText }}</q-badge>
      </q-banner>
    </div>
  </div>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "ProjectBanner",
  setup() {
    const projects = ref([
      {
        title: "Task Page",
        description:
          "A simple task management page built using JavaScript, CSS, and HTML. Users can add tasks with a designated title and description, and remove tasks as needed. The interface provides a clean and intuitive user experience for task management.",
        imageUrl: "/public/img/task.jpg",
        badgeText: "#HTML #CSS #JavaScript",
        url: "https://agustinvissani.github.io/reactvitejsfazt/",
      },
      {
        title: "Shop",
        description:
          "This project is an online store built using Vite, JavaScript, HTML, and CSS. Users can browse through a selection of items, add them to their shopping cart, and remove items as needed. The interface includes filtering options to help users easily find specific products they're interested in. It offers a seamless shopping experience with intuitive navigation and smooth interactions.",
        imageUrl: "/public/img/shop.jpg",
        badgeText: "#HTML #CSS #JavaScript #ViteJs",
        url: "https://agustinvissani.github.io/ecommerce-react-adv/",
      },
      {
        title: "TicTacToe",
        description:
          "This project is a classic Tic Tac Toe game implemented using JavaScript, HTML, and CSS. It features a 3x3 grid where two players take turns marking their respective symbols (X and O). The game includes logic to determine the winner or declare a draw, providing an interactive and enjoyable gaming experience for users. The simple and intuitive interface enhances the traditional Tic Tac Toe gameplay.",
        imageUrl: "/public/img/tictactoe.jpg",
        badgeText: "#HTML #CSS #JavaScript",
        url: "https://agustinvissani.github.io/tictactoe/",
      },
    ]);

    return {
      projects,
    };
  },
});
</script>

<style>
.description,
.button-link {
  color: white;
}

.button-link {
  background-color: rgb(19, 18, 18);
  padding: 8px 16px;
  border-radius: 4px;
  text-decoration: none;
  cursor: pointer;
  transition: background-color 0.3s;
}

.button-link:hover {
  background-color: #333;
}

.title {
  color: white;
  margin-bottom: 10px;
}

img {
  border-radius: 5px;
}
</style>
