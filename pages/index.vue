<template>
  <TemplateHome />
</template>

<script lang="ts">
import Vue from 'vue';
import TemplateHome from '@/components/templates/Home.vue';

export default Vue.extend({
  name: 'IndexPage',
  components: { TemplateHome },
});
</script>
