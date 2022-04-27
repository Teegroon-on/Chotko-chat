<template>
  <div class="h-full w-full flex flex-col">
    <aside class="bg-blue-600 w-full h-20">
      <img class="w-auto h-20" src="../assets/image/logo.jpg" alt="logo">
    </aside>
    <div class="min-h-screen w-full flex flex-col items-center justify-center">
     <div class="grid grid-rows-6 grid-cols-2 gap-2">
       <label class="mx-2 mt-0.5 text-xl">Введите Никнейм:</label>
       <input class="block px-1.5 py-1.5 bg-blue-300 border-blue-700 text-black rounded" type="text">
       <label class="mx-2 mt-0.5 text-xl">Введите Логин:</label>
       <input class="block px-1.5 py-1.5 bg-blue-300 border-blue-700 text-black rounded" type="text">
       <label class="mx-2 mt-0.5 text-xl">Введите email:</label>
       <input class="block px-1.5 py-1.5 bg-blue-300 border-blue-700 text-black rounded" type="text">
       <label class="mx-2 mt-0.5 text-xl">Введите пароль:</label>
       <input class="block px-1.5 py-1.5 bg-blue-300 border-blue-700 text-black rounded" type="text">
       <label class="mx-2 mt-0.5 text-xl">Повторите пароль:</label>
       <input class="block px-1.5 py-1.5 bg-blue-300 border-blue-700 text-black rounded" type="text">
      </div>
      <div class="flex">
        <button class="inline-block text-white bg-blue-600 font-medium rounded uppercase px-6 py-2.5 w-50 mr-2">Зарегистрироваться</button>
        <button class="inline-block text-white bg-blue-600 font-medium rounded uppercase px-6 py-2.5 w-50">Войти анонимно</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "registration"
}
</script>

<style src="../assets/css/main.css">

</style>
