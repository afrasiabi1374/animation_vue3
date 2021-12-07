<template>
  <div>
      <transition>
      <h1 v-if="myVar">we have this products</h1>
      <h1 v-else>we dont have this products</h1>
      </transition>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>