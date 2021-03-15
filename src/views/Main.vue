<template>
  <v-main>
    <v-container>
      <router-view/>
    </v-container>
  </v-main>
</template>

<script>
export default {
  name: 'Main',
  props: {
  },
  components: {
  },
  data: () => ({
  }),
  computed: {
  },
  mounted () {
  }
}
</script>
<style>
  main {
    min-width: 1024px;
  }
</style>
