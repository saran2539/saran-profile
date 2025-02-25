<template>
  <div>
    <!-- เพิ่ม Navbar -->
    <Navbar />
    <!-- NuxtPage ใช้ในการแสดงเนื้อหาของแต่ละหน้า -->
    <NuxtPage />
  </div>
</template>

<script setup>
// นำเข้า Navbar
import Navbar from '~/components/Navbar.vue'
</script>

<style scoped>
/* คุณสามารถเพิ่มสไตล์ที่ต้องการที่นี่ */
</style>

