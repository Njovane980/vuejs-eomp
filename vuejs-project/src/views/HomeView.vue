<template>
  <div class="landing">
    <h1 class="text-1 display-3">
      Hi!,
      I am Vuyiseka Njovane an aspiring full-stack developer.
    </h1>
  </div>
</template>

<script>
export default {
  name: 'homePage',
}
</script>

<style scoped>
.landing {
  position: relative;
  width: 100%;
  height: 100vh;
  background: url("C:/Users/Student/Downloads/background.jpg") center/cover no-repeat;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(255, 255, 255, 0.5);
}

.text-1 {
  position: absolute;
  top: 60%;
  margin: 20px;
  padding: 40px;
  right: 60%;
  transform: translate(-7%, -50%);
  color: black;
  font-weight: 120;
  text-align: center;
}

</style>