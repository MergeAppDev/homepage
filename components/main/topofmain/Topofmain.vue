<template>
  <div
    class="bg-center bg-cover bg-no-repeat pt-20 pb-14 mt-4 rounded-t-xl"
    style="
      background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(20, 20, 20)), url('/bg.png');
    "
  >
    <div class="justify-center">
      <p class="text-pink-400 text-xl font-normal text-center mb-2">
        Merge App | Beta
      </p>
      <p class="text-white text-4xl font-semibold text-center">
        A futuristic real-time messaging<br />platform
      </p>
      <div class="flex justify-center mt-2">
        <p class="md:w-1/2 w-10/12 justify-center text-gray-500 text-center">
            Our main goal is to make an application where people can securely message and create groups.
            Stay tuned for developer-specific markdown support, gamer-specific add-ons, and more...
        </p>
      </div>
    </div>
    <div class="flex justify-center ">
    <div class="md:w-auto w-3/4">
      <div class="flex justify-center">
        <div class="mt-4 group">
          <div
            class="
              md:flex
              bg-stone-800
              rounded-xl
              ease-in-out
              duraction-400
              transition-all
              shadow-lg
              group-hover:shadow-stone-800/50 group-hover:-rotate-5
              shadow-stone-900/50
            "
          >
            <input
              type="email"
              placeholder="Enter your email.."
              class="md:p-3 p-2 bg-transparent outline-none text-white font-medium"
            />
            <div class="flex md:p-4 p-2 bg-fuchsia-500 rounded-xl items-center">
              <button class="text-white">Request beta access</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Topofmain",
};
</script>