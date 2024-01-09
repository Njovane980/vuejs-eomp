<template>
  <div class="landing">
    <h1 class="text-1">
          Greetings! Welcome to
          <b class="storeName">Organic Cosmetic Wholesaler.</b> I'm Vuyiseka,
          and I'm delighted to have you here. Explore our diverse range of
          organic products designed to cater to your skincare needs.
        </h1>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.landing {
    width: 100vw;
    height: 100vh;
    background-image: url('../assets/css/background\ image_cleanup.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .text-1 {
    position: absolute;
    top: 50%; 
    left: 80%; 
    transform: translate(-50%, -50%); 
    color: white; 
    font-weight: 80;
    text-align: center;
}
</style>
