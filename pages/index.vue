<template>
  <div>
    <video class="video-bg" autoplay loop muted>
      <source src="/assets/video/f2b.mp4" type="video/mp4"  />
    </video>
  </div>
</template>

<script lang="ts">
// import SimpleButton from '../components/SimpleButton.vue';

export default {
  // components: {
  //   SimpleButton
  // }
}
</script>

<style scoped>
.video-bg{
   position: absolute;
   top: 0;
   left: 0;
   width: 100%;
   height: 100%;
   object-fit: cover;
   overflow: hidden;
}
</style>
