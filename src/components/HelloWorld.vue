<template>
  <div class="hello">
    <div class="name">
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
      <div class="letter">
      <img alt="Vue logo" src="../assets/logo.png" />
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HomeComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name{
  display: flex;
}
</style>
