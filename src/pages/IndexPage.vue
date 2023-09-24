<template>
  <div w-200 align="center">
    <unoSample

      mt-20
      title="unoCSS - test"
      subtitle="sample component"
      link="http://www.quasar.dev"

    />
    <quasarSample :actionTitle="'call help'"  w-60/>

  </div>
</template>

<script setup>
import unoSample from 'src/components/unoSample.vue';
import quasarSample from 'src/components/quasarSample.vue';

</script>

<style lang="scss" scoped>

</style>
