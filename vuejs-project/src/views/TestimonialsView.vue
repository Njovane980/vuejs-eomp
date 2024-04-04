<template>
  <div class="container">
    <h2 class="display-2" id="heading">Peer Reviews</h2>
    <div class="row">
      <div class="col-md-4" v-for="(review, index) in peerReviews" :key="index">
        <div class="card" @mouseover="showBack(index)" @mouseleave="hideBack(index)">
          <div class="card-inner">
            <div class="card-front">
              <img :src="review.image" :alt="review.name" class="profile-img">
              <h3>{{ review.name }}</h3>
            </div>
            <div class="card-back">
              <p>{{ review.testimony }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      peerReviews: [
        {
          name: 'Pinda Fortuin',
          image: 'https://i.postimg.cc/v87TF4wX/IMG-5879.jpg',
          testimony: 'Vuyiseka is a creative, professional, and well-behaved individual who always prioritizes her work. She excels in collaborating with others and has gained proficiency in HTML5, CSS, and Bootstrap. Including Git and GitHub.'
        },
        {
          name: 'Thimna Alam',
          image: 'https://i.postimg.cc/MGy2MjDF/IMG-5868.jpg',
          testimony: 'Vuyiseka has an infectious personality, always full of joy and never fails to bring a smile to your face. She has a strong interest in learning and developing herself and her skills as a developer. She is a joy to be in the presence of and works well with others. She will be a valuable member to any team.'
        },
        {
          name: 'Unathi Gcetywa',
          image: 'https://i.postimg.cc/cH93Q61Q/IMG-5869.jpg',
          testimony: 'I had the pleasure of working with Vuyiseka. Her dedication, expertise, and leadership is truly inspiring. She not only excelled in her technical skills but also brought a unique perspective to problem-solving and collaboration.'
        },
        {
          name: 'Natasha Kapeyi',
          image: 'https://i.postimg.cc/Wzd5ZBV1/IMG-5885.jpg',
          testimony: 'Vuyiseka is an incredibly hard worker. She has a strong sense of teamwork and is always willing to help others to the best of her ability'
        },
        {
          name: 'Sivuyisiwe Peter',
          image: 'https://i.postimg.cc/mgsSZzPD/IMG-5890.jpg',
          testimony: 'I highly recommend Vuyiseka Njovane as a software developer. Her technical expertise, commitment to quality, and strong communication skills makes her an asset to any team. I look forward to the opportunity to work with her again in the future.'
        },
        {
          name: 'Inganathi Stemela',
          image: 'https://i.postimg.cc/XNKS7FJG/IMG-5871.jpg',
          testimony: 'Vuyiseka is the most dedicated and goal driven person I have met. Her brightest feature is her boldness - she is never afraid to speak her mind, she is able to work on her tasks and finish them on time. I believe she would  be a good asset to any company.'
        },
        
      ],
      flippedIndex: null
    };
  },
  methods: {
    showBack(index) {
      this.flippedIndex = index;
    },
    hideBack() {
      this.flippedIndex = null;
    }
  }
};
</script>

<style scoped>
.container {
  padding-left: 140px;
}
.card {
  width: 250px;
  height: 300px;
  margin-bottom: 20px;
  position: relative;
  perspective: 1000px;
  box-shadow: 10px 20px 20px rgba(0, 0, 0, 0.525);
}

.card-inner {
  width: 100%;
  height: 100%;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.card:hover .card-inner {
  transform: rotateY(180deg);
}

.card-front,
.card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}

.card-front {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.card-back {
  transform: rotateY(180deg);
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 5px;
  color: black;
  padding: 10px;
}

.profile-img {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover ;
}

#heading {
  margin: 50px;
  padding-right: 140px;
}
</style>