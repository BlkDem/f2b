<template>
  <div>
    <marquee
      direction="down"
      behavior="alternate"
      width="90%"
      height="98%"
    >
      <marquee behavior="alternate">
        <h1><span class="text-bold primary">F2B Agency</span> - ваш проводник в мир цифрового будущего</h1>
      </marquee>
    </marquee>

    <video class="video-bg" autoplay loop muted>
      <source src="/assets/video/f2b.mp4" type="video/mp4"  />
    </video>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'F2B Agency',
  meta: [
    { name: 'description', content: 'F2B Agency - ваш проводник в мир цифрового будущего' }
  ],
  bodyAttrs: {
    // class: 'test'
  },
  // script: [ { innerHTML: 'console.log(\'Hello world\')' } ]
})

useSeoMeta({
  title: 'F2B Agency',
  ogTitle: 'F2B Agency',
  description: 'F2B Agency - ваш проводник в мир цифрового будущего',
  ogDescription: 'F2B Agency - ваш проводник в мир цифрового будущего',
})

</script>

<style scoped>

.text-bold {
  font-weight: 900;
}

.primary {
  color: rgb(232, 36, 36);
}

/* h1 {
  animation: flicker 1.5s infinite alternate;
} */

marquee {
  color: rgb(139, 173, 236);
  position: absolute;
  /* left: 30px;
  top: 20px; */
  z-index: 1;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
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
