<template>
   <div ma w-80>
    <div text-5xl fw100 animate-bounce-alt animate-count-infinite animate-duration-1s>
      {{props.title}}
    </div>
    <div op30 text-lg fw300 m1>
      {{props.subtitle}}
    </div>
    <div m2 flex justify-center text-2xl op30 hover="op80">
      <a href="{{props.link}}"><q-avatar color="red" text-color="white" icon="directions" /></a>


    </div>
  </div>

</template>

<script setup>
const props = defineProps({
  title: String,
  subtitle: String,
  link: String,
})



</script>

<style lang="scss" scoped>

</style>
