<template>
  <section class="section">
    <div class="container">
      <div class="columns">
        <div class="column">
          <center>
            <button class="button is-info is-large" @click="loginAction">Login</button>
          </center>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data () {
    return {}
  },
  props: ['loginAction']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
