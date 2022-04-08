<template>
  <dir>
    <div class="flex justify-center">
      <p class="text-3xl font-semibold text-gray-200 mb-4">Why should you choose us?</p>
    </div>
    <div class="flex justify-center text-gray-400">
      <div class="flex md:w-auto w-11/12 justify-center">
        <div class="grid grid-cols-3 gap-3">
          <div
            v-for="(Func, index) in Function"
            :key="index"
            class="
              flex
              justify-center
              items-center
              w-full
              text-center
              hover:scale-105
              transition-all
              duraction-200
              p-3
              bg-stone-800
              rounded-xl
            "
          >
            <p class="md:text-base text-sm">{{ Func.name }}</p>
          </div>
        </div>
      </div>
    </div>
  </dir>
</template>

<script>
export default {
  name: "Bottomofmain",
  data() {
    return {
      Function: [
        {
          name: "Private Calls",
        },
        {
          name: "Different Encryption System",
        },
        {
          name: "Lightweight App",
        },
        {
          name: "Fast Api",
        },
        {
          name: "Open Source",
        },
        {
          name: "Without any Restrictions",
        },
        {
          name: "2FA Support",
        },
        {
          name: "Powerful Guard System",
        },
        {
          name: "And more...",
        },
      ],
    };
  },
};
</script>