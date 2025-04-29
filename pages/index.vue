<template>
  <div>
    <h1>Welcome to My Vue App</h1>
    <p>This is a simple Vue.js application.</p>
    <router-view></router-view>
    <footer>
      <p>&copy; 2023 My Vue App. All rights reserved.</p>
    </footer>
    <div>
      <p>Contact us at: support@myvueapp.com</p>
    </div>
  </div>
</template>
<script setup>
useSeoMeta({
  title: "Main Page",
  description: "This is the main page",
  ogTitle: "Main Page",
  ogDescription: "This is the main page",
  ogImage: "[og:image]",
  ogUrl: "[og:url]",
  twitterTitle: "Main Page",
  twitterDescription: "[og:description]",
  twitterImage: "[og:image]",
  twitterCard: "summary_large_image",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
  link: [
    {
      rel: "icon",
      href: "image/png",
      href: "/favicon.png",
    },
  ],
});
</script>
