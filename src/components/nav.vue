<template>
<div class="nav navbar-collapse">
    <ul class="nav justify-content-center bg-transparent">
    <li class="nav-item">
      <a class="nav-link active" aria-current="page" href="#"><router-link to="/"> Home</router-link></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#"><router-link to="/about"> About</router-link></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#"><router-link to="/projects"> Projects</router-link></a>
    </li>
        <li class="nav-item">
         <a class="nav-link"><router-link to="/skills"> Skills</router-link></a>
       </li>
    <li class="nav-item">
      <a class="nav-link"><router-link to="/test"> Testimonials</router-link></a>
    </li>
     <li class="nav-item">
      <a class="nav-link"><router-link to="/contact"> Contact</router-link></a>
    </li>
  </ul>
</div>
</template>

<script>
export default {

}
</script>

<style>
a{
    text-decoration: none;
    font-family: Rocket;
    color:#67b3e4 ;
    font-size: 20px;
}
a:hover{
    color:white;
}
.nav{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    background-color: black ;

}
</style>