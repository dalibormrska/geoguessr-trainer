<template lang="pug">
div
  AppHeader
  h1 About 
  p Memorization trainer for Geoguessr
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
