<template>
  <div>
    <Navbar class="sticky top-0"/>
    <MainTopofmain />
    <MainBottomofmain />
    <Footer />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

body {
    background-color: rgba(20, 20, 20);
    font-family: 'Inter', sans-serif;
}

</style>

<script>
export default {
  head: {
    title: 'Home | MergeApp',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'my website description'
      }
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }]
  }
}
</script>