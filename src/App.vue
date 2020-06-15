<template>
  <div id="app">
    <!-- <Skills msg="Welcome to Your Vue.js App"/>
     -->

     <router-view/>
  </div>
</template>

<script>

</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
  @import "../node_modules/bootstrap/scss/bootstrap.scss";



#app{
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  color: #2c3e50;
}


ul{
    margin:0 !important;
    padding:0;
    li{
        list-style-type: none;
    }
}

h1, h2, h3, h4, h5, h6{
    margin: 0 !important;
    padding: 0;
}
p{
    margin: 0 !important;
}



section {
    padding: 50px 0 60px;
}

</style>
