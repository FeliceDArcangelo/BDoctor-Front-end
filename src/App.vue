<script >
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'app',
  components: {
    AppHeader,
    AppFooter
},
  data() {
    return {


    }
  },
  created() {

  },
  mounted() {

  },
  methods: {


  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <RouterView></RouterView>
  <AppFooter></AppFooter>

</template>

<style scoped>

</style>
