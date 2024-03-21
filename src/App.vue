<script>
import AppHeader from './components/AppHeader.vue';

export default {
  name: 'App',
  data() {
    return {
      title: 'Hello World!'
    }
  },
  components: {
    AppHeader
  }
}

</script>

<template>
  <h1>{{ title }}</h1>

  <AppHeader></AppHeader>

</template>

<style></style>
