<template>
    <div>
        <img src="https://itz-marcus.github.io/Project_images/4th_page_clear.png" alt="backgrounds2" loading="lazy">
        <div id="container">
          <div v-for ="project in projectData()" :key="project.name">
            <div id="Card">
                <div  class="card" style="margin-top: 10%;border-radius: 0px; width: 17rem; height: 19vw; background-color: rgba(0, 0, 0, 0.544);color: white;box-shadow:0px 1px 1px 4px  rgb(255, 199, 1);" >
                    <img id="card-cover" :src= 'project.image'  class="card-img-top" alt="...">
                    <div id="proj-b" class="card-body">
                        <h5 id="proj-t" class="card-title">{{project.name}}</h5>
                        <p id="proj-tx" class="card-text">{{ project.description }}</p>
                        <a id='button' :href='project.gitHub' target="_blank" class="btn btn-primary">Github</a>
                        <a id='button' :href='project.vercel' target="_blank" class="btn btn-primary">See live</a>
                    </div>
                </div>  
            </div> 
        </div>  
        </div>
    </div>
</template>
<script>
export default {
    methods:{
        projectData(){
            return this.$store.state.projects
        }
    },
    computed:{
        getAboutMe(){
            return this.$store.dispatch("getAboutMe")
        }
    },
    mounted(){
        this.getAboutMe
    }   
}
</script>
<style scoped>
#button{
    border: 2px solid rgb(255, 199, 1);
    background-color: rgb(255, 199, 1);
    color: black;
    font-weight: bold;
    width: 7vw;
    border-radius: 0px;
    border: 0px; 
    transition: 0.3s;
    margin-right: 6px;
}
#button:hover{
    box-shadow: 3px 4px 0px rgb(255, 199, 1);
    border: 2px solid rgb(255, 199, 1);
    background-color:black ;
    color: rgb(255, 199, 1);
}
#Card{
    transition: 0.3s;
}
#Card:hover{
    box-shadow: 10px 10px 0px rgb(255, 199, 1);
    background-color: black;
    transform: scale(1.02);
}
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
#container{
    display: grid;
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