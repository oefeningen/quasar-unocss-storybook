<template>
  <div>
    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">
      <q-card-section>
        <div class="text-h6">coloured squares</div>
        <div class="text-subtitle2">by John Doe</div>
        <div flex items-center justify-between>
          <div w-10 h-10 bg-red></div>
          <div w-10 h-10 bg-green></div>
          <div w-10 h-10 bg-blue></div>
          <div w-10 h-10 bg-yellow></div>
        </div>
      </q-card-section>
      <q-card-section>
         <q-btn color="white" text-color="black" :label="actionTitle" />

      </q-card-section>
    </q-card>
  </div>
</template>

<script setup>
const props=defineProps({
  actionTitle:String

})

</script>

<style lang="scss" scoped>

</style>
