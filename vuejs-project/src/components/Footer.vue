<template>
    <div class="container-fluid">
        <div class="row">
            <p class="lead">Designed by Vuyiseka Njovane &copy;
                <span> {{ currYear}}</span>
            </p>
        </div>

    </div>
    <div class="social-icons">
          <a href="https://www.linkedin.com/in/vuyiseka-njovane-104504239/" target="_blank" class="linkedin"><i class="fab fa-linkedin"></i>LinkedIn</a>
          <a href="https://github.com/Njovane980" target="_blank" class="github"><i class="fab fa-github"></i>Github</a>
          <a href="#" target="_blank" class="phone"><i class="fab fa-phone"></i>+27 671454980</a>
    </div>
</template>

<script>
    export default {
        name: 'FooterComp',
        data() {
            return{
                currYear: new Date().getFullYear()
        }
        
    }
}
</script>

<style scoped>

.social-icons {
  margin-top: 2px;
  font-size:x-small;
}

.social-icons a {
  color: black;
  font-size: 15px;
  margin-right: 2%;
}

.social-icons a:last-child {
  margin-right: 0;
}
</style>