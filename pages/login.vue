<template>
    <div>

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
    <div class="flex min-h-screen bg-gray-100 items-center justify-center">
      <div class="bg-white p-8 rounded shadow-md w-full max-w-md">
        <h1 class="text-2xl font-semibold mb-4">Login</h1>
        <form>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-medium mb-2" for="username">Username</label>
            <input
              type="text"
              id="username"
              v-model="username"
              class="border rounded w-full p-2 focus:outline-none focus:ring focus:border-blue-300"
            />
          </div>
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-medium mb-2" for="password">Password</label>
            <input
              type="password"
              id="password"
              v-model="password"
              class="border rounded w-full p-2 focus:outline-none focus:ring focus:border-blue-300"
            />
          </div>
          <a href="/login"><button class="mt-4 text-slate-200 bg-slate-800 rounded-md shadow-md p-4 px-6 hover:bg-slate-200 hover:text-slate-800">Login </button></a>
        </form>
      </div>
    </div>
</div>
  </template>
  
  <script>
  </script>
  
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap');
  </style>