<template>
    <div class="headings">
      <h1 class="display-3">Resume</h1>
      <h4 class="display-5">Education</h4>
    </div>
    <div class="main-timeline">
            <div class="timeline">
                <div class="icon"></div>
                    <div class="date-content">
                        <div class="date-outer">
                            <span class="date">
                            <span class="year">2023</span>
                            </span>
                        </div>
                    </div>
                    <div class="timeline-content">
                        <h5 class="title"> Life Choices Coding Academy</h5>
                        <p class="description">
                            Full-Stack Web Development
                        </p>
                    </div>
                </div>
                                           
                <div class="timeline">
                    <div class="icon"></div>
                    <div class="date-content">
                        <div class="date-outer">
                            <span class="date">
                            <span class="year">2019- <p>2023</p></span>
                            </span>
                        </div>
                    </div>
                    <div class="timeline-content">
                        <h5 class="title">University of Fort Hare</h5>
                        <p class="description">
                            Bachelor of Social Science in Human Settlement
                        </p>
                        <p>Bachelor of Social Science Honours in Project Management</p>
                    </div>
                </div>
                                            
                <div class="timeline">
                <div class="icon"></div>
                <div class="date-content">
                        <div class="date-outer">
                            <span class="date">
                            <span class="year">2016</span>
                            </span>
                        </div>
                    </div>
                    <div class="timeline-content">
                        <h5 class="title">Matsa High School</h5>
                        <p class="description">
                            National Senior Certificate
                        </p>
                    </div>
                </div>
            </div>
            <div class="headings">
                <h4 class="display-5">Skills</h4>
                <div class="row grid gap-3" id="row">
                <div class="flip-card">
                <div class="flip-card-inner">
                  <!-- Front of the card -->
                  <div class="flip-card-front">
                    <img src="../assets/html logo.png" alt="HTML Logo" class="logo">
                    <h3>HTML</h3>
                  </div>
                  <!-- Back of the card -->
                  <div class="flip-card-back">
                    <p>Proficient in HTML5 for building structured web pages.</p>
                  </div>
                </div>
              </div>
            
              <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <img src="../assets/css.png" alt="CSS Logo" class="logo">
                    <h3>CSS</h3>
                  </div>
                  <div class="flip-card-back">
                    <p>Skilled in CSS for styling and layout of web pages.</p>
                  </div>
                </div>
              </div>
            
              <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <img src="../assets/Javascript.png" alt="JavaScript Logo" class="logo">
                    <h3>JavaScript</h3>
                  </div>
                  <div class="flip-card-back">
                    <p>Experience with JavaScript for interactive web development.</p>
                  </div>
                </div>
              </div>
            
              <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <img src="../assets/bootstrap logo.png" alt="Bootstrap Logo" class="logo">
                    <h3>Bootstrap</h3>
                  </div>
                  <div class="flip-card-back">
                    <p>Proficient in Bootstrap for responsive and mobile-first design.</p>
                  </div>
                </div>
              </div>
            </div>
            <div>
            </div>
        </div>
    </template>
<style scoped>
.main-timeline {
     position: relative
 }
 
 .main-timeline:before {
     content: "";
     display: block;
     width: 2px;
     height: 100%;
     background: #090458;
     margin: 0 auto;
     position: absolute;
     top: 0;
     left: 0;
     right: 0
 }
 
 .main-timeline .timeline {
     margin-bottom: 40px;
     position: relative
 }
 
 .main-timeline .timeline:after {
     content: "";
     display: block;
     clear: both
 }
 
 .main-timeline .icon {
     width: 18px;
     height: 18px;
     line-height: 18px;
     margin: auto;
     position: absolute;
     top: 0;
     left: 0;
     bottom: 0;
     right: 0
 }
 
 .main-timeline .icon:before,
 .main-timeline .icon:after {
     content: "";
     width: 100%;
     height: 100%;
     border-radius: 50%;
     position: absolute;
     top: 0;
     left: 0;
     transition: all 0.33s ease-out 0s
 }
 
 .main-timeline .icon:before {
     background: white;
     border: 2px solid #232323;
     left: -3px
 }
 
 .main-timeline .icon:after {
     border: 2px solid #c6c6c6;
     left: 3px
 }
 
 .main-timeline .timeline:hover .icon:before {
     left: 3px
 }
 
 .main-timeline .timeline:hover .icon:after {
     left: -3px
 }
 
 .main-timeline .date-content {
     width: 50%;
     float: left;
     margin-top: 22px;
     position: relative
 }
 
 .main-timeline .date-content:before {
     content: "";
     width: 36.5%;
     height: 2px;
     background: #0000ff;
     margin: auto 0;
     position: absolute;
     top: 0;
     right: 10px;
     bottom: 0
 }
 
 .main-timeline .date-outer {
     width: 125px;
     height: 125px;
     font-size: 16px;
     text-align: center;
     margin: auto;
     z-index: 1
 }
 
 .main-timeline .date-outer:before,
 .main-timeline .date-outer:after {
     content: "";
     width: 125px;
     height: 125px;
     margin: 0 auto;
     border-radius: 50%;
     position: absolute;
     top: 0;
     left: 0;
     right: 0;
     transition: all 0.33s ease-out 0s
 }
 
 .main-timeline .date-outer:before {
     background: #fff;
     border: 2px solid #232323;
     left: -6px
 }
 
 .main-timeline .date-outer:after {
     border: 2px solid #0000ff;
     left: 6px
 }
 
 .main-timeline .timeline:hover .date-outer:before {
     left: 6px
 }
 
 .main-timeline .timeline:hover .date-outer:after {
     left: -6px
 }
 
 .main-timeline .date {
     width: 100%;
     margin: auto;
     position: absolute;
     top: 27%;
     left: 0
 }
 
 .main-timeline .month {
     font-size: 18px;
     font-weight: 700
 }
 
 .main-timeline .year {
     display: block;
     font-size: 30px;
     font-weight: 700;
     color: #232323;
     line-height: 36px
 }
 
 .main-timeline .timeline-content {
     width: 50%;
     padding: 20px 0 20px 50px;
     float: right
 }
 
 .main-timeline .title {
     font-size: 19px;
     font-weight: 700;
     line-height: 24px;
     margin: 0 0 15px 0
 }
 
 .main-timeline .description {
     margin-bottom: 0
 }
 
 .main-timeline .timeline:nth-child(2n) .date-content {
     float: right
 }
 
 .main-timeline .timeline:nth-child(2n) .date-content:before {
     left: 10px
 }
 
 .main-timeline .timeline:nth-child(2n) .timeline-content {
     padding: 20px 50px 20px 0;
     text-align: right
 }
 
 @media only screen and (max-width: 991px) {
     .main-timeline .date-content{
         margin-top: 35px
     }
     .main-timeline .date-content:before {
         width: 22.5%
     }
     .main-timeline .timeline-content {
         padding: 10px 0 10px 30px
     }
     .main-timeline .title {
         font-size: 17px
     }
     .main-timeline .timeline:nth-child(2n) .timeline-content {
         padding: 10px 30px 10px 0
     }
 }
 
</style>
