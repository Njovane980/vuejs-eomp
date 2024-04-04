<template>
  <h2 class="display-2" id="heading">Projects</h2>
  <div class="container d-flex justify-content-center" id="Projct">
    <div class="row gap-3" id="rows">
      <div v-for="(project, index) in projects" :key="index" class="p-2 g-col-6 card w-25" :class="{ 'slide-from-left': index % 2 === 0, 'slide-from-right': index % 2 !== 0 }">
        <div class="card-body">
          <img :src="project.image" class="card-img-top" :alt="project.title">
          <h5 class="card-title text-dark">{{ project.title }}</h5>
          <a :href="project.github" class="btn btn-outline-dark" target="_blank">GitHub</a>
          <a :href="project.netlify" class="btn btn-outline-dark" target="_blank">Netlify</a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      projects: [
        {
          title: "The Calculator",
          image: "https://i.postimg.cc/Bvyt9bZQ/calculator.jpg",
          github: "https://github.com/Njovane980/CalculatorTask.git",
          netlify: "#"
        },
        {
          title: "Capstone Project",
          image: "https://i.postimg.cc/YqnHyVCt/cap.jpg",
          github: "https://github.com/Njovane980/CaptoneEOMP.git",
          netlify: ""
        },
        {
          title: "Node.js Project",
          image: "https://i.postimg.cc/dQRddRt2/node.jpg",
          github: "",
          netlify: ""
        },
        {
          title: "JavaScript Project",
          image: "https://i.postimg.cc/9XP8Mq6S/download.jpg",
          github: "https://github.com/Njovane980/MyJSEOMP.git"
        },
        {
          title: "Online weave store",
          image: "https://i.postimg.cc/RhrZbYSP/hair.jpg",
          github: ""
        },
        {
          title: "The BMI calculator",
          image: "https://i.postimg.cc/267KPbmP/th.jpg",
          github: "https://github.com/thimnaalam/MobiCare_week1.git"
        }
      ]
    };
  }
};
</script>

<style scoped>

.card {
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
  height: 300px;
  width: 300px;
  margin-right: 0px;
  
  
}
img{
  height: 200px;
}
.btn {
  background-color: gray;
  border-color: white;
  box-shadow: 10px 7px 10px rgba(0, 0, 0, 0.1);
}
h2 {
  font-family: "Arvo", serif;
  margin-top: 5%;
  padding-left: 20px;
}
.slide-from-left {
  animation: slideFromLeft 1s ease-in-out;
}
.slide-from-right {
  animation: slideFromRight 1s ease-in-out;
}
@keyframes slideFromLeft {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}
@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(0);
  }
}


@media (max-width: 300px) {
  .card {
    width: 100%; 
    margin-right: 0;
  }
}
</style>
  