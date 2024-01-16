<template>
  <div class="comment-box">
    <img src="../assets/avatars/image-amyrobson.png" alt="Amy Broson">
    <textarea placeholder="Add comment..."></textarea>
    <button class="btn-primary" @click="handleConsole">Reply</button>
  </div>
</template>

<script setup>
const handleConsole = () => {
  console.log('test')
}

</script>