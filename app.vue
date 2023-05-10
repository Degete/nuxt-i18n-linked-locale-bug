<template>
  <div>
    <p>This is to test the bug with linked messages</p>
    <p>Translate message: {{  t('welcome') }}</p>
  </div>
</template>

<script setup lang="ts">
const { t } = useI18n()
</script>