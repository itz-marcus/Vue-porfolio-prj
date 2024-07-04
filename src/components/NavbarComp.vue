<template>
  <div>
    <nav id="navbar">
          <router-link to="/">Home</router-link>
          <router-link  to="/about">About</router-link>
          <router-link id="nav3" to="/resume">Resume</router-link>
          <router-link  to="/projects">Projects</router-link>
          <router-link id="nav5" to="/testimonials">Testimonials</router-link>
          <router-link  to="/contact">Contact</router-link>
    </nav> 
  </div>
</template>

<script>
export default {
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* -------- nav bar -------- */
nav a {
  margin: 6%;
  font-weight: bold;
  color: white;
  text-decoration: none;
  rotate: -90deg;
  transition: 0.3s;
  font-size: 2.4vh;
}
nav a:hover{
  color: rgb(255, 199, 1);
  text-decoration:underline;
}
nav a.router-link-exact-active {
  color:rgb(255, 199, 1);
}
#navbar{
    height: 73vh;
    display: flex;
    justify-content:space-evenly;
    flex-direction: column;
    gap: 5%;
    width: 70px;
}
#nav3 {
    margin-bottom: 20%;
}
#nav5 {
    margin-top: 65%;
    margin-bottom: 10%;
}
</style>
