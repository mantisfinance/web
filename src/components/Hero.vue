<template>
  <section id="hero" class="text-gray-600 body-font">
    <div class="container mx-auto flex px-5 py-10 items-center justify-center flex-col">
      <Mantis3d></Mantis3d>
      <div class="text-center lg:w-2/3 w-full">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Get ready to devour <u>DeFi</u></h1>
        <p class="mb-8 leading-relaxed">Join our communities and learn more</p>
        <div class="flex justify-center">
          <button class="text-black bg-transparent border border-solid border-black hover:bg-purple-400 hover:text-white active:bg-purple-700 font-bold uppercase px-3 py-3 rounded-full outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
            <img alt="Telegram" src="img/icons/telegram.svg" width="20">
          </button>
          <button class="text-black bg-transparent border border-solid border-black hover:bg-yellow-500 hover:text-white active:bg-yellow-700 font-bold uppercase px-3 py-3 rounded-full outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
            <img alt="Discord" src="img/icons/discord.svg" width="20">
          </button>
          <button class="text-black bg-transparent border border-solid border-black hover:bg-blue-400 hover:text-white active:bg-blue-700 font-bold uppercase px-3 py-3 rounded-full outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
            <img alt="Medium" src="img/icons/medium.svg" width="20">
          </button>
          <button class="text-black bg-transparent border border-solid border-black hover:bg-pink-400 hover:text-white active:bg-pink-700 font-bold uppercase px-3 py-3 rounded-full outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
            <img alt="Twitter" src="img/icons/twitter.svg" width="20">
          </button>
          <button class="text-black bg-transparent border border-solid border-black hover:bg-green-500 hover:text-white active:bg-green-700 font-bold uppercase px-3 py-3 rounded-full outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
            <img alt="Github" src="img/icons/github.svg" width="20">
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Mantis3d from 'Components/Mantis3d.vue';
export default {
  name: 'Hero',
  components: {
    Mantis3d,
  },
  setup() {
    return {
    };
  }
};
</script>
