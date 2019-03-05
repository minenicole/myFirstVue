<template>
  <div :class="['logo', {selected} ? 'logo--absolute': '', {ready} ? 'logo--active' : '']" @click="closePost()">
  </div>
</template>

<script>
export default {
  name: 'Post'
}
</script>

<style lang="sass">
  @import ../assets/styles/style
</style>
