<template lang="">
    <div>
        <img src="https://itz-marcus.github.io/Project_images/5th_page_clear.png" alt="backgrounds2" loading="lazy">
        <div class="card" style=" margin-left:0.7%;margin-top: 3.5%; width: 17rem; height: 32rem;background-color: rgba(0, 0, 0, 0.708);color: white;box-shadow:0px 1px 1px 4px  rgb(255, 230, 0);" >
                <img id="card-cover" src="https://itz-marcus.github.io/Project_images/M-B.png" class="card-img-top" alt="...">
                <div id="proj-b" class="card-body">
                  <h5 id="proj-t" class="card-title">Mathew Dean Brown</h5>
                  <p id="proj-tx" class="card-text">"Marcus is very creative and has an eye for design. Loves to help others and  works well in a team. I would recommend him for his talent and dedication to his work."</p>
                  
                </div>
              </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
img[alt='backgrounds2']{
    height: 74vh;
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
.card{
    font-size: 20px;
}
#card-cover{
    border-radius: opx;
    width: 100%;
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
    height: 20%;
    width: 100%;
    object-fit: contain;
}  
</style>