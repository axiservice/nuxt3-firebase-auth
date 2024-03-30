<template>
  <div>
    <div>--------------Secret 2-----------------------</div>
  </div>
</template>

<script setup>
definePageMeta({
  middleware: ["auth"],
});

const firebaseUser = useFirebaseUser();
</script>

<style></style>
