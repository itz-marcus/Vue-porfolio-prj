<template>
    <div>
        
        <img src="https://itz-marcus.github.io/Project_images/5th_page_clear.png" alt="backgrounds2" loading="lazy">
        <section id="section">
            <div v-for ="testimonial in testimonialData()" :key="testimonial">
                <div>
                    <div id="Card" class="card" style="margin: 10%; border-radius: 0px; width: 200px; height: 17vw; background-color: rgba(0, 0, 0, 0.544);color: white;box-shadow:0px 1px 1px 4px  rgb(255, 199, 1);" >
                        <!-- <img id="card-cover" :src= 'testimonial.image'  class="card-img-top" alt="..."> -->
                        <div id="proj-b" class="card-body">
                            <h5 id="proj-t" class="card-title">{{testimonial.name}}</h5>
                            <p id="proj-tx" class="card-text">{{ testimonial.message }}</p>
                        </div>
                    </div>  
                </div> 
            </div> 
        </section>

    </div>
</template>
<script>
export default {
    methods:{
        testimonialData(){
            return this.$store.state.testimonials
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
<style scoped >
#section{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    
}
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
#Card{
    transition: 0.3s;
}
#Card:hover{
    box-shadow: 10px 10px 0px rgb(255, 199, 1);
    background-color: black;
    transform: scale(1.02);
}
.card{
    font-size: 20px;
}
.card:hover{
    box-shadow: 4px 4px 0px rgb(255, 199, 1);
}
#card-cover{
    border-radius: opx;
    width: 10vw;
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