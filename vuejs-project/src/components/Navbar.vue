<template>
    <nav class="navbar navbar-expand-lg ">
  <div class="container-fluid">
    <!-- <a class="navbar-brand" href="#">Navbar</a> -->
    <router-link to="/">
        <img class="img-fluid" src="../assets/VN (2).png" height="50px" alt="logo">
    </router-link>
    <!-- replace the a tag with the router link for the home page -->
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-1 mb-lg-0">
        <li class="nav-item">
            <router-link to="/" class="nav-link active text-white ">
                Home
            </router-link>
          <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
        </li>
        <li class="nav-item">
            <router-link to="/about" class="nav-link text-white">
                    About
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/resume" class="nav-link text-white ">
                    Resume
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/project" class="nav-link text-white">
                    Projects
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/testimonials" class="nav-link text-white">
                    Testimonials
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/contact" class="nav-link text-white">
                    Contact
            </router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
      name: 'NavBarComp'
    }
</script>

<style scoped>
.nav-link {
    font-size: x-large;
}

</style>