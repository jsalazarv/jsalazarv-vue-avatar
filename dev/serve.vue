<script lang="ts">
import Vue from 'vue';
import VAvatar from '@/v-avatar.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VAvatar
  }
});
</script>

<template>
  <div id="app">
    <v-avatar />
  </div>
</template>
