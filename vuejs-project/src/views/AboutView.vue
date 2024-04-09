<template>
  <h2 class="display-2" id="heading">About Me</h2>
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <div class="about-picture">
          <img :src="profilePicture" alt="Profile Picture">
        </div>
      </div>
      <div class="col-md-6">
        <div class="about-content">
          <p>{{ aboutText }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      profilePicture: 'https://i.postimg.cc/fW7svvyC/skill-blog-img.jpg',
      aboutText: `I was born on 27 August 1997 in King Williams Town in the Eastern Cape but currently residing in Makhaza, Khayelitsha in Cape Town. I am a dedicated individual who has completed matric in 2016 and completed a Bachelor of Social Sciences Human Settlements (Property and Development). In addition to my academic achievements, I have pursued a comprehensive full-stack development course from Life Choices Coding Academy, and I am currently undertaking studies in Cybersecurity. I am deeply committed to continuous learning and personal development, recognizing them as fundamental pillars of professional growth and excellence. I firmly believe in the empowerment of women and actively engage with campaigns and initiatives dedicated to advancing this noble cause. Currently, I am gaining practical experience and honing my skills as an intern at LC Studio, where I am contributing to various projects and furthering my understanding of the industry. I approach my work with diligence, professionalism, and a steadfast commitment to excellence.In my free time, I learn new skills I also enjoy reading books.`
    };
  }
};
</script>


<style scoped>
.container {
  margin-top: 50px;
  border: 2px solid #ab9c9c; 
  border-radius: 10px; 
  padding: 20px; 
}

.about-picture img {
  max-width: 100%;
  border-radius: 5px;
}

.about-content h2 {
  font-size: 40px;
  margin-bottom: 70px;
}

.about-content p {
  font-size: 15px;
  line-height: 1.6;
}
</style>

