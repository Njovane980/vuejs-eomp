<template>
    <div class="headings">
      <h2 class="display-3">Projects</h2>
    </div>
    <div class="row grid gap-3 mx-auto" id="rows">
                    
                <div class="p-2 g-col-6 card w-25" style="width: 18rem;">
                    <img src="../assets/calculator logo.jpg" class="card-img-top" alt="calculator-logo">
                    <div class="card-body">
                      <h5 class="card-title">Calculator</h5>
                      <a href="https://github.com/Njovane980/CalculatorTask.git" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                <div class="p-2 g-col-6 card w-25" style="width: 18rem;">
                    <img src="../assets/mobicare logo.png" class="card-img-top" alt="mobicare-logo">
                    <div class="card-body">
                      <h5 class="card-title">Mobicare</h5>
                      <a href="https://github.com/Njovane980/MobiCare.git" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                <div class="p-2 g-col-6 card w-25" style="width: 18rem;">
                    <img src="../assets/weave.jpg" class="card-img-top" alt="weave">
                    <div class="card-body">
                      <h5 class="card-title">Weave Online Store</h5>
                      <a href="" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                <div class="p-2 g-col-6 card w-25" style="width: 18rem;">
                    <img src="../assets/keyboard.jpg" class="card-img-top" alt="keyboard">
                    <div class="card-body">
                      <h5 class="card-title">Keyboard</h5>
                      <a href="https://github.com/Njovane980/KyboardTask.git" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                <div class="p-2 g-col-6 card w-25" style="width: 18rem;">
                    <img src="../assets/to do list.jpg" class="card-img-top" alt="ToDoList">
                    <div class="card-body">
                      <h5 class="card-title">To Do List</h5>
                      <a href="https://github.com/Njovane980/ToDoList.git" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                <div class="p-2 g-col-6 card w-25 " style="width: 18rem;">
                    <img src="../assets/BMI.jpg" class="card-img-top" alt="BMIConverter">
                    <div class="card-body">
                      <h5 class="card-title">BMI Converter</h5>
                      <a href="https://github.com/Njovane980/BMICalculator.git" class="btn btn-primary">Git Hub</a>
                      <a href="#" class="btn btn-primary">Netlify</a>
                    </div>
                  </div>
                </div>

  </template>
  
  <script>
    export default {
        
    }
  </script>
  
<style scoped>
#rows{
    padding-left: 20px;
    margin-top: 40px;
} 
@media (max-width: 300px) {
  #rows {
    padding-left: 10px;
  }
  .card {
    width: 100%; /* Adjust the width as needed */
  }
}

/* Media Query for screens with a maximum width of 576px (typical mobile devices) */
@media (max-width: 576px) {
  #rows {
    padding-left: 15px;
  }
  .card {
    width: 100%; /* Adjust the width as needed */
  }
}

/* Media Query for screens with a maximum width of 720px */
@media (max-width: 720px) {
  #rows {
    padding-left: 20px;
  }
  .card {
    width: 100%; /* Adjust the width as needed */
  }
}
</style>
  