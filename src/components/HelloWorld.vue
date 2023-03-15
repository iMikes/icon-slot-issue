<template>
 <v-icon>
   <slot />
 </v-icon>
</template>

<script>

export default {
  name: 'HelloWorld',
  mounted()
  {
    window.console.log('HelloWorld mounted', this.$slots.default());
  },
}
</script>
