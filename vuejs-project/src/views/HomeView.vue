<template>
  <div class="content">
    <div class="container">
      <div class="info">
        <h1 class="fullname">Vuyiseka Njovane</h1>
        <p>Hi, I am a Certified Full-stack developer,<br> profiecient in multiple technologies and have a proven track
          record of <br>time management and adaptability. <br>Commited to finding constructive solutions to challenges<br> and work well in collaborative teams.
        </p>
        <a href="https://drive.google.com/file/d/1yYYJd4BbxeFTwAFXQOsSuOghJngnDdNm/view?usp=sharing" class="resume-button" loading="lazy">Download my resume</a>
      </div>
      <div class="image">
        <img src="https://i.postimg.cc/SK9Jvgr1/312cb784-9dcf-4e57-802c-97e63a8e3e4e-1.jpg" alt="Profile Picture">
      </div>
    </div>
  </div>
</template>

<style scoped>
.content {
  background-image: url('https://i.postimg.cc/2S4zLGQn/circles2.webp');
  background-size: cover;
  background-position: center;
}

.container {
  display: flex;
  align-items: center;
  gap: 20px; /* Adjust the gap as needed */
  min-height: calc(100vh - 80px);
}

@media (max-width: 767px) {
  .container {
    flex-direction: column-reverse;
    gap: 0;
    min-height: calc(100vh - 101px);
  }
}

.image {
  flex: 1;
}

.fullname {
  font-size: 3rem; 
}

.image img {
  max-width: 100%;
  border-radius: 80%; 
}

.info {
  flex: 1;
  text-align: center; 
}

.info h1 {
  color: black;
  font-size: 60px;
}

.resume-button {
  display: inline-block;
  background-color: black;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 20px; /* Adjust margin as needed */
}
</style>

