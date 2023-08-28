<template>
  <div class="font-poppins"> 

    
    <nav class="flex space-x-4 justify-between px-6 mt-2">
      <div>
        <h1 class="text-blue-500 text-lg">Cerku</h1>
      </div>
      <div class="text-lg ">
        <a href="/" class="font-medium  px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900 ">Home</a>
        <a href="/login" class="font-medium px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">login</a>
        <a href="/about" class="font-medium px-3 py-2 text-slate-700 rounded-lg hover:bg-slate-100 hover:text-slate-900">about</a>
      </div>
      <h1>Your profile</h1>
    </nav>
    <div class="flex flex-col h-screen md:flex-row md:bg-cover md:bg-center" style="background-image: url(https://images.theconversation.com/files/463677/original/file-20220517-20-r8xyl6.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=1356&h=668&fit=crop);">
      <div class="flex justify-center items-center md:w-1/2">
        <img class="max-h-80 md:max-h-full rounded-sm shadow-sm ml-2" src="https://penerbitdeepublish.com/wp-content/uploads/2016/06/cara-membuat-buku.jpg" alt="Buku">
      </div>
      <div class="flex flex-col justify-center items-center p-6 md:w-1/2 text-slate-100">
        <h1 class="text-4xl font-medium text-center mb-4 md:text-left">Selamat Datang di <span class="text-blue-500">cerKu</span></h1>
        <h2 class="text-lg text-center md:text-left">"Temukan Inspirasi, Tulis Cerpenmu! Menjadi Penulis Kisah Tak Terbatas dalam Genggamanmu."</h2>
        <a href="/login"><button class="mt-4 bg-slate-800 rounded-md shadow-md p-4 px-6 hover:bg-slate-200 hover:text-slate-800">Login now</button></a>
      </div>
    </div>
    <footer class="bg-gray-900 text-white py-4">
      <div class="container mx-auto text-center">
        <p>&copy; 2023 cerKu. All rights reserved.</p>
        <p>Designed with <span class="text-red-500">&hearts;</span> by Muhammad Alif Mujaddid</p>
      </div>
    </footer>
    
    
    </div>


</template>

<script>
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap');
</style>