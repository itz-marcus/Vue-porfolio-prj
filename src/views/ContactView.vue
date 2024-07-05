<template lang="">
    <div class="contact">
        <img src="https://itz-marcus.github.io/Project_images/6th_page_clear.png" alt="backgrounds3" loading="lazy">
        <section class="d-flex ">

            
<div id="End-title-b">
    <h2 id="End-title">Let's get in <b>touch!</b></h2>
    <p id="contact-space"><b>Contact me</b></p>
    <p id="contactinfo-space">Email: marcusadonis5@gmail.com <br> Number: +2782 929 5821 <br> Location: Mitchell's Plain</p>
</div>
<div></div>
<div id="end-space">
    <form id="Style"
    action="https://formspree.io/f/xvoedppj"
method="POST" 
    >
        <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Name</label>
            <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
            name="name">
          </div>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Email address</label>
          <input name="email" type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
        <div class="mb-3">
          <label for="exampleInputPassword1" class="form-label">Message</label>
          <textarea type="text" class="form-control" id="exampleInputPassword1"
          name="message"></textarea>
        </div>
        <button id="Button-style" type="submit" class="btn btn-primary">Submit</button>
      </form>
</div>
</section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    img[alt='backgrounds3']{
    height: 120vh;
    top: -6%;
    background-repeat: no-repeat;
    opacity: 0.5; 
    position: fixed;
    z-index: -1;
    left: 10%;
    margin-left: auto;
    margin-right:auto;
    object-fit: contain;
}
h2{
    font-weight:bolder;
    color: white;
    line-height: 0.95;
    
}
b{
    color: rgb(255, 199, 1);
    font-size: 35px;
}
#End-title-b{
    width: 40%;    
}

#End-title{
    font-size: 9vw;
    width: 80%;
    line-height: 0.95;
    margin-top: 10%;
    margin-left:12%
}
#End-title b{
    font-size: 9vw;
}
#Style{
    color: white;
}
#Button-style{
    background-color: rgb(255, 199, 1);
    color: black;
    font-weight: bold;
    width: 8vw;
    border-radius: 0px;
    border: 0px;
}
#end-space{
    margin-top: 10%;
    margin-left: 20%;
}
#contact-space{
    margin-left: 16%;
    font-size:2vw;
}
#contactinfo-space{
    margin-left: 16%;
    color: rgb(255, 199, 1) ;
}
#end-space input{
    width: 30rem;
    border: rgb(255, 199, 1) solid 2px;
    border-radius: 0px;
}
.form-control{
    background-color: rgba(0, 0, 0, 0.515);
    color: white;
}
p b {
    font-size: 3vw;
}
textarea{
    border: rgb(255, 199, 1) solid 2px;     
    height: 13vw;
    border-radius: 0px;
}
#contactinfo-space{
    color: white;
}
#contact-space{
    text-decoration: underline rgb(255, 199, 1);

}
</style>