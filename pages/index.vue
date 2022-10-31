<template lang="pug">
div
  AppHeader
  div.grid.grid-cols-12.grid-gap-8
    AppAside.col-span-3.sticky
    #content.container.mx-auto.pr-4.col-span-9
      section.pt-20  
        h1.text-8xl Geoguessr Trainer
        h2.text-2xl Tool for practicing your metas

        ul
          li
            svg.icon
            a(href="/") Licence Plates

  AppFooter
  
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'Trainer',
  head() {
    return {
      title: 'Geoguessr Trainer',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Best place to practice Geoguessr',
        },
      ],
    }
  },
})
</script>
