<template>
  <div class="headings">
    <h2 class="display-3">About</h2>
    <div class="container">
      <div class="image-container">
        
        <img src="https://i.postimg.cc/jqG54FLm/IMG-5799.jpg" id="abtpic" alt="Your Picture" >
      </div>
      <div class="contents">
        
        <p class="para1">
          I am Vuyiseka Njovane, born on 27 August 1997. Originally from King William's Town, a small historical town in the Eastern Cape.
          I now currently reside on Tutu Avenue, Makhaza in Khayelitsha.
          I matriculated with a Bachelor pass from Matsa High School in 2016, pursued higher education
          from the University of Fort Hare where I graduated in 2023 with a Bachelor of Social Science in Human Settlements.
          Changed careers and ventured into the tech industry, enrolled at Life Choices Coding Academy where I recently graduated 
          from a Full-stack development course. In my free time, I read and study.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.headings {
  background-image: url('https://i.postimg.cc/2S4zLGQn/circles2.webp');
  background-size: cover;
  background-position: center;
  height: 700px; /* Adjust height as needed */
}

.container {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(2, 13, 13, 0.156);
  width: 1000px;
  margin-top: 5%;

}

.image-container {
  flex: 1; /* To occupy 50% of the container */
}

.image-container img {
  width: 100%;
  height: auto;
  max-width: 100%; /* Ensures the image does not exceed its container */
}

.contents {
  flex: 1; 
  padding: 100px;
 

}

.display-3 {
  margin-top: 0; 

}

.para1 {
  margin-top: 0; 
}

#abtpic{
 height: 500px;
 object-fit: contain;
}
</style>

