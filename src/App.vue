<script>
import AppTitle from './components/AppTitle.vue'
export default (await import('vue')).defineComponent({
  components: {
    AppTitle
  }
})
</script>

<template>
  <AppTitle />
</template>

<style scoped>

</style>
