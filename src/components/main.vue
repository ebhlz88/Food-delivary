<template>
  <div>
      <div class="sticky">
      <div class="flex-container">
         <span @click="hide"><i class="fa-solid fa-bars"></i></span>
          
          <p class="navitem"><b>Foodlogics</b></p>
          <div class="toleft">
            <i class="fa-solid fa-bell navitem"></i>
          <img class="profile-img navitem" src="../assets/murad.jpg" alt="profile">
          <p>Adam schwart</p>
          </div>
          
      </div>
      </div>
      <div
      class="side-navbar active-nav d-flex justify-content-between flex-wrap flex-column"
      id="sidebar"
    >
    <div class="flex-container">
        <img src="../assets/murad.jpg" class="profile-img navitem" alt="profile">
        <div >
            <p class="nametext">harm ten nepal</p>
            <p class="username">beheerder</p>
        </div>
    </div>
    <hr>
        
      <ul class="nav flex-column w-100">
          <p>Navigation</p>
        <li href="#" class="nav-link">
          <i class="fa-solid fa-bell navitem"></i>
          <a class="mx-2">Dashboard</a>
        </li>
        <li href="#" class="nav-link">
          <i class="fa-solid fa-list navitem"></i>
          <span class="mx-2">Orders</span>
        </li>
        <li href="#" class="nav-link">
          <i class="fa-solid fa-user navitem"></i>
          <span class="mx-2">Relations</span>
        </li>
      </ul>
    </div>
    <hr>
    <container class="relative"/>
  </div>
</template>

<script>
import container from "./container.vue"
export default {
    name:'mainn',
    components:{
        container
    },
    data(){
      return{
        y:false,
      }
    },
methods:{
    hide(){
        if(this.y===false){
            // var element = document.getElementById("sidebar");
            //  element.classList.add("side-navbar");
            document.getElementById("sidebar").style.display = "block";
            
        this.y=true
        console.log(this.y)}
        else if(this.y===true){
          
        document.getElementById("sidebar").style.display = "none";
             this.y=false
             console.log(this.y)
        }

        
        // console.log(y)
    }
}
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  min-height: 100vh;
  background-color: #fff;
}
.flex-container{
    display: flex;
    padding: 10px;
    align-items: center;
    margin-left: 8px;
}
.profile-img{
    height: 30px;
    border-radius: 50%;
    margin-left: auto;
}
.toleft{
    display: flex;
    margin-left: auto;
    align-items: center;
    justify-content: center;
}
.navitem{
    margin: 0px 10px;
}
.nametext{
    font-size: 95%;
}
.username{
    font-size: 70%;
}
.nav p{
    text-align: left;
    margin-left: 20px;
    
}
#sidebar .flex-container{
    margin-left: 0px;
    padding: 10px 0px;
}
#sidebar .profile-img{
    height: 40px;
    border-radius: 50%;
}
.nav{
    padding: 30px 8px;
    font-size: 88%;
    list-style-type: none;
}



.side-navbar {
  width: 220px;
  height: 100%;
  display: none;
  position: fixed;
  /* margin-left: -300px; */
  color: rgb(184, 184, 184);
  background-color: #1d2228;
  transition: 0.5s;
}
.nav-link{
    text-align: left;
    padding: 15px 10px;
}

.nav-link:active,
.nav-link:focus,
.nav-link:hover {
  background-color: #424242;
   border-radius: 25px;
  padding: 20px;
  width: 200px;
  color: rgb(233, 233, 233);
}

.my-container {
  transition: 0.4s;
}

.active-nav {
  margin-left: 0;
}

/* for main section */
.active-cont {
  margin-left: 180px;
}

#menu-btn {
  background-color: #100901;
  color: #fff;
  margin-left: -62px;
}

.my-container input {
  border-radius: 2rem;
  padding: 2px 20px;
}
.fa-bars:hover{
  cursor: pointer;
}
.sticky{
  background-color: #ffffff;
    position:fixed;
    top:0;
    width:100%;
    z-index:100;
}
.relative{
  margin-top: 41px !important;
}

</style>