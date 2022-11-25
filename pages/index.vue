<template>
  <div>
    <h3>home</h3>
    <nuxt-link :to="'/about'">about</nuxt-link>
  </div>
</template>

<script>
export default {
    name:'IndexPage',
    data() {
      return {
        title: 'Home page'
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Home page description'
          }
        ]
      }
    }
}
</script>
