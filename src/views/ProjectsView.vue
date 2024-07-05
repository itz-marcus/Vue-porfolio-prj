<template lang="">
    <div>
        <img src="https://itz-marcus.github.io/Project_images/4th_page_clear.png" alt="backgrounds2" loading="lazy">
        <img src="https://itz-marcus.github.io/Project_images/4th_page_clear.png" alt="backgrounds2" loading="lazy">
        <div class="card" style="margin-top: 10%; width: 17rem; height: 20rem; background-color: rgba(0, 0, 0, 0.544);color: white;box-shadow:0px 1px 1px 4px  rgb(255, 230, 0);" >
                <img id="card-cover" src="https://itz-marcus.github.io/Project_images/keyboardW.png" class="card-img-top" alt="...">
                <div id="proj-b" class="card-body">
                  <h5 id="proj-t" class="card-title">Keyboard</h5>
                  <p id="proj-tx" class="card-text">Made a winnie the pooh styled keyboard. HTML & CSS styling keyboard project</p>
                  <a href="https://github.com/itz-marcus/Keyboard" target="_blank" class="btn btn-primary">Github</a>
                  <a href="https://keyboard-one-snowy.vercel.app/" target="_blank" class="btn btn-primary">See live</a>
                </div>
              </div>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
img[alt='backgrounds2']{
    height: 75vh;
    top:10%;
    background-repeat: no-repeat;
    opacity: 0.5; 
    position: absolute;
    z-index: -1;
    left: 15%;
    margin-left: auto;
    margin-right:auto;
    object-fit: contain;
}
#proj-b{
    background-color:transparent;
}
#proj-tx{
    font-size: 70%;
    color: white;
}
.card-cover{
    height: 50%;
    width: 100%;
}
</style>