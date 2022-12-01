<template>
    <img
    :src="props.image"
    class="profile"
    alt="profile"
  />
</template>       

<script setup>

const props = defineProps ({
    // name: String, 
    image: String, 
    // handle: String,
    // timestamp: String,
    // message: String
})

</script>

<style scoped>

</style>