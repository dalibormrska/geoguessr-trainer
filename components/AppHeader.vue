<template lang="pug">
div
  nav.py-8.bg-white.boder.shadow
    .container.mx-auto.px-4.flex.justify-between
      .img
        img(src="../static/Logo.png")
      ul.flex.justify-end.text-xl.gap-8
        li.nav-item
          NuxtLink(to='/') Trainer
        li.nav-item
          NuxtLink(to='/about') About
    
</template>

<script>
export default {}
</script>

<style></style>
