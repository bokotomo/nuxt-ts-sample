<template>
  <TemplateAbout />
</template>

<script lang="ts">
import Vue from 'vue';
import TemplateAbout from '@/components/templates/About.vue';

export default Vue.extend({
  name: 'AboutPage',
  components: { TemplateAbout },
});
</script>
