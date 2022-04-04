<template>
  <div>
    <Navbar class="sticky top-0"/>
    <div
      class="bg-center bg-cover bg-no-repeat py-20 mt-4 rounded-t-xl"
      style="background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(20, 20, 20)), url('static/bg.png')">
      <div class="justify-center">
          <p class=" text-pink-400 text-xl font-normal text-center mb-2">Merge App | Beta</p>
          <p class="text-white text-4xl font-semibold text-center">A futuristic real-time messaging<br/>platform</p>
            <div class="flex justify-center mt-2">
              <p class="md:w-1/2 w-10/12 justify-center text-gray-500 text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
            </div>
      </div>
          <div class="flex justify-center mt-4 group ">
            <div class="flex bg-stone-800 rounded-xl ease-in-out duraction-400 transition-all shadow-lg group-hover:shadow-stone-800/50 group-hover:-rotate-5 shadow-stone-900/50">
              <input type="email" placeholder="Enter your email.." 
              class="p-3 bg-transparent">
              <div class="flex p-4 bg-fuchsia-500 rounded-xl items-center">
                <button class="text-white">Request beta access</button>
              </div>
            </div>
          </div>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

body {
    background-color: rgba(20, 20, 20);
    font-family: 'Inter', sans-serif;
}

</style>