<template>
  <div id="app">
      <introduction/>
  </div>
</template>

<script>
import Introduction from './components/Introduction.vue';

export default {
  name: 'App',
  components: {
    Introduction
  },
};
</script>

<style lang="scss">
    @import '~bulma/bulma.sass';
    @import '~normalize.css';

    #app {
        background-color: #f8f8f8;
    }
</style>
