<template>
  <router-view/>
  <img src="https://itz-marcus.github.io/Project_images/1st_page_clear.png" alt="bgimage" loading="lazy">
  <img src="https://itz-marcus.github.io/Project_images/Logo.png" alt="logo" loading="lazy">
  <div class="home">
    <div>
        <div id="title">
          <h1 id="home-title">Hi,<br> I'm <br><p>Marcus</p></h1>
        </div>
        <div id="sub">
          <p class="sub-title">An Aspiring Web Developer!</p>
        </div>
        <div id="socials">
          <a href="https://github.com/itz-marcus" target="_blank"><i class="lab la-github"></i></a>
          <a href="https://za.pinterest.com/marcusadonis5/my-saves/" target="_blank"><i class="lab la-pinterest-p"></i></a>
          <a href="https://www.linkedin.com/in/marcus-adonis-9a28512b6/" target="_blank"><i class="lab la-linkedin-in"></i></a>
        </div>
          
    </div>
        <div class="effects">
          <img src="https://itz-marcus.github.io/Project_images/PoloBanner.gif" alt="banner" loading="lazy">   
          <img src="https://itz-marcus.github.io/Project_images/globe.gif" alt="globe" loading="lazy">  
          <img src="https://itz-marcus.github.io/Project_images/media_controller.png" alt="m-player" loading="lazy">
          <img src="https://itz-marcus.github.io/Project_images/visualizer.gif" alt="visualizer" loading="lazy">
        </div> 
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  }
}
</script>
<style scoped>

@media screen and (max-width:750px){
  #border h1{
    font-size: 70px;
    margin-top:7vh ;
  }
  #home-title p{
    font-size: 70px;  
  }
  img[alt='logo']{
    width: 80px;
    object-fit: contain;
    height: 7vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top: 5%;
    left: 40%;
  }
  #sub .sub-title{
    font-size: 4vw;
    width: 52vw;
  }
  .effects img[alt='banner']{
    right: 9vw;
}
}
#home-title{
    margin-top: 10%;
    width: 40vw;
    font-size: 10vw;
    margin-left: 10%;
    font-weight:bolder;
    color: white;
    line-height: 0.95;
    margin-bottom: 0px;   
}  
h1 p{
    color:rgb(255, 199, 1);
    font-size: 10vw;
}
.sub-title{
    font-size: 2vw;
    margin-left: 10%;
    font-weight:bolder;
    color: white;
    font-family: "Lekton", monospace;
    font-style:normal;
    margin-top: 0px;
}
#socials{
  margin-left: 4%;
}
i{ 
    font-size: 45px;
    color: white;    
    margin-left: 4%;
    font-weight: lighter;
    cursor: pointer;
    transition: 0.2s;
    
}
i:hover{
    color: rgb(255, 199, 1);
    text-shadow: 0px 2px 0px  rgb(53, 53, 53) ;
    transform: scale(120%);
}
img[alt='bgimage']{
    width: 985px;
    height: auto;
    background-repeat: no-repeat;
    opacity: 0.5; 
    position: fixed;
    z-index: -1;
    left: 20%;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
img[alt='logo']{
    height: 7vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top: 5%;
    left: 46%;
    /* margin-left: auto;
    margin-right:auto; */

}
img[alt='banner']{
    height: 56vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top: 5vh;
    right: 5vw;
    margin: 2px;
}
img[alt='globe']{
    height: 10vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top:62vh;
    right: 3.5vw;
    margin: 2px;
}
img[alt='visualizer']{
    height: 17vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top:58vh;
    right: 6vw;
    margin-right: 10px;
}
img[alt='m-player']{
    height: 10vh;
    background-repeat: no-repeat; 
    position: absolute;
    z-index: -1;
    top:73vh;
    right: 3.5vw;
    margin: 2px;
}
</style>

