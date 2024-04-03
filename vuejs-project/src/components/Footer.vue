<template>
    <div class="container">
        <div class="row">
            <p class="lead">Vuyiseka Njovane Portfolio &copy;
                <span> {{ currYear}}</span>
            </p>
        </div>

    </div>
    <div class="social-icons">
          <a href="https://i.postimg.cc/DZvrqVQ3/linkedin.png" target="_blank" class="linkedin"><i class="fab fa-linkedin"></i></a>
          <a href="https://i.postimg.cc/RVPvm2Vp/github.png" target="_blank" class="github"><i class="fab fa-github"></i></a>
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
}

.social-icons a {
  color: black;
  font-size: 30px;
  margin-right: 2%;
}

.social-icons a:last-child {
  margin-right: 0;
}
</style>