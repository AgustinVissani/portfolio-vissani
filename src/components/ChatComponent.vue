<template>
  <div class="q-pa-md row justify-center">
    <div style="width: 100%; max-width: 400px">
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Welcome!, I am Agustín Danel Vissani, an enthusiastic systems analyst. Pleased to meet you.',
        ]"
        stamp="17 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="['How are you today?']"
        size="6"
        stamp="14 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'I\'m fine thanks.',
          ' Excited for this opportunity and ready to talk about my experience and how I can contribute to the team.',
        ]"
        stamp="14 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'I\'m glad to hear that!',
          ' Before we begin, would you mind telling me a little about yourself?',
        ]"
        size="6"
        stamp="13 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Of course.',
          'I am Agustín Danel Vissani, an enthusiastic systems analyst with a great passion for technology and problem solving.',
          'I have been immersed in the world of computing since an early age, which led me to obtain my secondary degree in \'PERSONAL AND PROFESSIONAL COMPUTER TECHNICIAN\.',
          'Later I continued studying and received my degree in \'SYSTEMS ANALYST\'.',
        ]"
        stamp="12 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'Sounds awesome, Agustín. ',
          'Can you tell me a little more about your previous experience?',
        ]"
        size="6"
        stamp="11 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Of course.',
          'Recently, as a Frontend developer in a personal project as a freelancer, I had the responsibility of developing an application using React. This involved creating a modular, component-based structure, integrating APIs with dynamic communication between the application and the server through Axios, and designing the interface using libraries such as Tailwind CSS and DaisyUI.',
        ]"
        stamp="10 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'Interesting. And what has your experience been like in previous roles? ',
        ]"
        size="6"
        stamp="9 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Previously, at Connectis S.A., I worked as a QA Tester on a project for Telefónica in Uruguay. My responsibility included performing regression, usability, compatibility and functionality testing, following the Agile methodology.',
          'Additionally, at MAS Tecnología, I played the role of warehouse assistant, where I acquired practical skills in PC assembly and warehouse operations at a technology wholesaler.',
        ]"
        stamp="9 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="['Excellent! Could you add IT SKILLS?']"
        size="6"
        stamp="9 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="['Sure, I\'ll leave them here']"
        stamp="9 minutes ago"
        sent
        bg-color="amber-7"
      />
    </div>
  </div>

</template>

<script>
export default {
  name: "ChatComponent",
  data() {
    return {
      showName: false,
    };
  },
};
</script>

<style scoped>

</style>
