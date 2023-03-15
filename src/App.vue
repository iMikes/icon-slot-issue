<template>

  <HelloWorld> mdi-magnify </HelloWorld>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  created()
  {
    this.console = window.console;
  },
};
</script>
