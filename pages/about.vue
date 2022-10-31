<template lang="pug">
div
  AppHeader
  #content.container.mx-auto.px-4
    h1.text-4xl About 
    .section
      h2 Memorization trainer for Geoguessr
  AppFooter
</template>

<script>
export default {
  head() {
    return {
      title: 'About The App',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Best place to practice Geoguessr',
        },
      ],
    }
  },
}
</script>

<style></style>
