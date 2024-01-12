  <template>
    <div class="headings">
      <h1 class="display-3">Testimonials</h1>
    </div>
    <div class="row vh-100 justify-center-center align-content-center">
            <div id="carouselExampleCaptions" class="carousel slide">
                <div class="carousel-indicators bg-success">
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="5" aria-label="Slide 6"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="../assets/joel2 (1).jpg" class="d-block w-25   mx-auto" loading="lazy" alt="image 1">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Joel Mukanya</h3>
                      <p>Vuyiseka is a creative, professional, and well-behaved individual who always prioritizes her work. She excels in collaborating with others and has gained proficiency in HTML5, CSS, and Bootstrap. Including Git and GitHub.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="https://i.imgur.com/zWOqJ1a.jpg" class="d-block w-25 mx-auto" loading="lazy" alt="image 2">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Damon Raffels</h3>
                      <p>Vuyiseka has an infectious personality, always full of joy and never fails to bring a smile to your face. She has a strong interest in learning and developing herself and her skills as a developer. She is a joy to be in the presence of and works well with others. She will be a valuable member to any team.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="https://i.imgur.com/gVoVRNo.jpg" class="d-block w-25 mx-auto" alt="image 3">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Akeefah Jones</h3>
                      <p>I had the pleasure of working with Vuyiseka. Her dedication, expertise, and leadership is truly inspiring. She not only excelled in her technical skills but also brought a unique perspective to problem-solving and collaboration.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="../assets/vero.jpg" class="d-block w-25 mx-auto" alt="image 4">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Veronique Nappie</h3>
                      <p>Vuyiseka is an incredibly hard worker. She has a strong sense of teamwork and is always willing to help others to the best of her ability. Although the world of coding is something new to her, I've seen her take on the challenge with a lot of courage and without looking back. Watching her go through this challenge indicates to me that she perseveres through her challenges and her ability to do this will carry very far. I believe she has a lot of potential for leadership because she is great at communicating her ideas in a concise manner. Vuyiseka and her drive to succeed will be invaluable to any team she is a part of.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="https://i.imgur.com/YYpkyjS.jpg" class="d-block w-25 mx-auto" alt="image 5">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Zubair Moerat</h3>
                      <p>I highly recommend Vuyiseka Njovane as a software developer. Her technical expertise, commitment to quality, and strong communication skills makes her an asset to any team. I look forward to the opportunity to work with her again in the future.</p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="https://i.imgur.com/6yzXy09.jpg" class="d-block w-25 mx-auto" alt="image 6">
                    <div class="carousel-caption opacity-75 bg-secondary d-none d-md-block">
                      <h3>Unathi Gcetywa</h3>
                      <p>Vuyiseka is the most dedicated and goal driven person I've met. Her brightest feature is her boldness - she is never afraid to speak her mind, she is able to work on her tasks and finish them on time. I believe she would  be a good asset to any company.</p>
                    </div>
                  </div>
                <button class="carousel-control-prev bg-dark" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next bg-dark" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
            </div>
            </div>
    </div>
  </template>
  
  <script>
    export default {
        
    }
  </script>
  
  <style scoped>
  .carousel-item {
    position: relative;
}

.image-container {
    position: relative;
    overflow: hidden;
}

.carousel-caption {
    position: absolute;
    bottom: 0;
    left: 20;
    right: 10;
    padding: 15px;
    justify-content: center;
    background-color: rgba(0, 0, 0, 0.75);
    color: #fff;
}

  </style>