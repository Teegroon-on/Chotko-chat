<template>
  <div class="h-full">
    <div class="h-full flex flex-col items-center justify-center">
      <img class="w-auto mx-auto" src="../assets/image/logo.jpg" alt="logo">
      <h2 class="h-1 font-bold text-center text-2xl">Чат</h2>
      <button class="inline-block text-white bg-blue-600 font-medium rounded uppercase px-6 py-2.5 w-96 mt-10">Авторизоваться</button>
      <nuxt-link to="/registration">
        <button class="inline-block text-white bg-blue-600 font-medium rounded uppercase px-6 py-2.5 w-96 my-2">Зарегистрироваться</button>
      </nuxt-link>
      <button class="inline-block text-white bg-blue-600 font-medium rounded uppercase px-6 py-2.5 w-96">Войти как анонимный пользователь</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',

  methods:{

  }
}
</script>

<style src="../assets/css/main.css"></style>
