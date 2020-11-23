<template>
  <div id="top" class="container">
    <a :href="url" target="_blank" style="color: #000;">go to the link. click me.</a>
  </div>
</template>

<script>
export default {
  layout: 'resume',
  data () {
    return {
      url: 'https://drive.google.com/file/d/1hQmvsGr_bSivcO5mlvAolymo93nN9RXK/view?usp=sharing'
    }
  },
  mounted () {
    this.init()
  },
  methods: {
    init () {

    }
  }
}
</script>

<style scoped>
.cc-contact-information {
  background-size: cover;
}
</style>
