<template>
    <h2 class="display-2" id="heading">Education</h2>
    <div class="container">
      <div class="section">
        <div class="timeline">
          <div class="timeline-item" v-for="(edu, index) in education" :key="index">
            <div class="timeline-content">
              <h3>{{ edu.degree }}</h3>
              <p>{{ edu.institution }}</p>
              <p>{{ edu.year }}</p>
            </div>
          </div>
        </div>
      </div>
      <div class="section">
        <h2 class="display-2" id="heading">Work Experience</h2>
        <div class="timeline">
          <div class="timeline-item" v-for="(exp, index) in experience" :key="index">
            <div class="timeline-content">
              <h3>{{ exp.title }}</h3>
              <p>{{ exp.company }}</p>
              <p>{{ exp.duration }}</p>
              <p>{{ exp.description }}</p>
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
              education: [
                  {
                      degree: "Cybersecurity Basics Certificate",
                      institution: "Life Choices Studio",
                      year: "2024 - Present"
                    },
                    {
                        degree: "Full-Stack Development Certificate",
                        institution: "Life Choices Coding Academy",
                        year: "2023 - 2024"
                    },
                    {
                        degree: "Bachelor of Social Sciences in Human Settlements",
                        institution: "University of Fort Hare",
                year: "2019 - 2023"
            },
            // Add more education entries as needed
            {
              degree: "National Senior Certificate",
              institution: "Matsa High School",
              year: "2016"
            },
        ],
        experience: [
          {
            title: "Software Developer Intern",
            company: "LC Studio",
            duration: "2024 - Present",
            description: "Contributing to various projects, gaining practical experience in web development, collaborated with team members."
          },
          {
            title: "Assistant Project Coordinator",
            company: "Department of Social Development",
            duration: "2022 - 2023",
            description: "Assisting in the development of project plans, timelines, and schedules. Coordinating meetings, preparing agendas, and documenting meeting minutes."
          },
          
        ]
      };
    }
  };
  </script>
  
  <style scoped>

  .container {
    max-width: 800px;
    margin: 0 auto;
  }
  
  .section {
    margin-bottom: 40px;
  }
  
  .timeline {
    position: relative;
  }
  
  .timeline-item {
    position: relative;
    padding: 20px;
    background-color: #7f7b7b63;
    border-radius: 8px;
    margin-bottom: 20px;
  }
  
  .timeline-content {
    margin-left: 40px;
  }
  
  .timeline-item::after {
    content: '';
    position: absolute;
    width: 2px;
    background-color: #0f0a0a;
    top: 0;
    bottom: 0;
    left: 20px;
    margin-left: -1px;
  }
  
  #heading {
    margin-bottom: 40PX;
  }
  </style>
  