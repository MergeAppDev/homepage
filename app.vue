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
const description = "A futuristic real-time messaging platform"

export default {
  head: {
    title: "Home | MergeApp",
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: description
      },
      {
        hid: 'twitter:card',
        name: 'twitter:card',
        content: 'summary',
      },
      {
        hid: 'twitter:site',
        name: 'twitter:site',
        content: '@mergeappdotdev',
      },
      {
        hid: 'twitter:creator',
        name: 'twitter:creator',
        content: '@mergeappdotdev',
      },
      {
        hid: 'twitter:title',
        name: 'twitter:title',
        content: 'mergeapp.dev',
      },
      {
        hid: 'twitter:description',
        name: 'twitter:description',
        content: description,
      },
      {
        hid: 'twitter:image',
        name: 'twitter:image',
        content: '/logo.png',
      },
      /* Open-Graph */
      {
        hid: 'og:title',
        name: 'og:title',
        content: 'MergeApp.',
      },
      {
        hid: 'og:type',
        name: 'og:type',
        content: 'website',
      },
      {
        hid: 'og:site_name',
        name: 'og:site_name',
        content: 'mergeapp.dev',
      },
      {
        hid: 'og:description',
        name: 'og:description',
        content: description,
      },
      {
        hid: 'og:image',
        name: 'og:image',
        content: '/logo.png',
      },
      /* Others */
      {
        hid: 'theme-color',
        name: 'theme-color',
        content: '#d946ef',
      },
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/logo.ico' }]
  }
}
</script>