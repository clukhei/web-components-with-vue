<script setup lang="ts">
import Footer from './components/Footer.vue'
import "@govtechsg/sgds-web-component"
import Mainnav from './components/Mainnav.vue'
</script>

<template>
  <Mainnav />
  <body>
   <sgds-template-grid>
    <sgds-content-area>
      <sgds-content-body>
        Hello world
      </sgds-content-body>
    </sgds-content-area>
   </sgds-template-grid>
  </body>
  <Footer/>
</template>

<style scoped>
body {
  display: flex;
  min-height: 80vh;
  flex-direction: column;
}
</style>
