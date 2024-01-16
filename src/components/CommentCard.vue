<template>
  <div class="comment-card">
    <div class="rating">
      <div @click="count++">
        <img src="../assets/icon-plus.svg" alt="icon plus">
      </div>
      <p>{{ count }}</p>
      <div @click="count--">
        <img src="../assets/icon-minus.svg" alt="icon minus">
      </div>
    </div>

    <img src="../assets/avatars/image-amyrobson.png" alt="Amyr bobson">
    <h5>Amyrbobson</h5>
    <span>1 month ago</span>
    <p>Impressive! Though it seems the drag feature could be improved. But overall it looks incredible. You've nailed the design and the responsiveness at various breakpoints works really well.</p>
  </div>
</template>



<script setup>
// import { resIcons } from '../resources';
import { ref } from 'vue';
// import data from '../db/data.json'

const count = ref(0)


</script>