<template lang="pug">
v-app
  router-view
</template>

<script setup>
</script>

<script setup>
import { useUserStore } from '@/stores/user'
useUserStore().getUser()
</script>
