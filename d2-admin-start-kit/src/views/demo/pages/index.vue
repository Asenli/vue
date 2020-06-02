<template>
  <d2-container better-scroll>
    <template slot="header">
      this.$store.dispatch('d2admin/menu/asideCollapseSet', true)
    </template>
    Hello World
    <template slot="footer">footer</template>
  </d2-container>
</template>

<script>
export default {
  name: 'index',
  mounted () {
    debugger
    // console.log(this.$store.dispatch('d2admin/menu/asideCollapseSet', false))
  }
}
</script>

<style scoped>

</style>
