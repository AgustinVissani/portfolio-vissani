<template>
  <div class="q-pa-md row justify-center">
    <div class="col-lg-8 col-md-6 col-sm-12">
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'Very good!',
          'Could you show me some of the projects you have developed?',
        ]"
        size="6"
        stamp="14 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Yes of course.',
          'I leave you a link so you can see them.',
        ]"
        stamp="17 minutes ago"
        sent
        bg-color="amber-7"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "ChatComponent2",
  data() {
    return {
      showName: false,
    };
  },
};
</script>

<style scoped></style>
