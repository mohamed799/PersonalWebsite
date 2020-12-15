<template>
  <div>
<!--    This is a comment used CTRL+/ -->
    <h1 class="WebHeader">
      {{ name }}!
    </h1>
    <button @click="setname">
      Change Name
    </button>
  </div>
</template>
<style>
/*This is a comment -- Used CTRL + / */
.WebHeader {
  color: #ff0000
}
</style>
<script>
export default {
  name: "home",
  data() {
    return {
      name: "Vikram"
    }
  },
  methods: {
    setname() {
      this.name = "Matthew and Mohamed"
    }
  }

}
</script>