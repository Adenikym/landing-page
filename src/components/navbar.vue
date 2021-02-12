<template>
    <div class="col-lg-12 px-0 " style="font-family: 'Roboto', sans-serif;" >
<div style="background-color:#FDBEDB;height:50px;color:black;font-family: 'Playfair Display', serif;
" class="top-grey col-lg-12 d-lg-flex  px-0  d-none">
    <p class="advice col-lg-2 mt-2 ">
        Lorem, ipsum dolor.
    </p>

    <p class="info col-lg-5 offset-lg-1 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>

<div class="menwear col-lg-2 d-flex offset-lg-2"> 
 <div class="box px-1 offset-lg-5"> <p class=" mt-3">MENSWEAR</p></div> 

    <div class="dropdown show ml-2 mt-3 ">
  <a class=" dropdown-toggle" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
   
  </a>

  <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
    <a class="dropdown-item" href="#">Action</a>
  
  </div>
</div>

</div>
</div>
<!-- top bar-->

<!-- larger screens-->

<div class="site-name col-lg-12 d-lg-flex d-none py-2">

    

    <div class="country col-lg-3 offset-lg-1 d-lg-flex d-none mt-3">
      <p style="height:25px;  border-right:1px solid grey;" class="px-1">United Kingdom, £ GBP
</p>  
      <p style="height:30px" class="ml-1">English</p>
    </div>

   


    <h1 class="col-lg-4 ">Styleest</h1>
    
    <div class="mini-nav d-lg-flex d-none col-lg-3 mt-3">
<div class="col-lg-2 icon">
<img src="../assets/star.svg"  width="18px" alt="">
</div>
<div class="col-lg-2 icon">
    <img src="../assets/shop.svg"  width="18px" alt="">
</div>
<div class="col-lg-3 px-1 " style="border-right:1px solid grey;height:20px;"><p>Register</p></div>
<div class="ml-2"> <p>Sign In</p> </div>
    </div>
</div>

 <!--smaller screens-->

<div class="s-topbar d-md-flex col-md-12 d-lg-none">
    <div class="menu  col-md-2 mt-3">
    <img src="../assets/menu.svg" width="25px" alt="">
</div>

  <h1 class=" col-md-3 offset-md-2">Styleest</h1>

  <div class="icons">
      <img src="../assets/shop.svg"  width="18px" alt="">
       <img src="../assets/search.svg"  width="18px" alt="">
  </div>
</div>

<!-- topbar ends-->

<!-- navbar -->

<div  class="top-nav col-lg-12 col-md-12 d-lg-flex d-none">
    <ul class="col-lg-10 col-md-11">
        <li  >NEW ARRIVALS</li>
        <li>DESIGNERS</li>
        <li>CLOTHING</li>
        <li>SHOES</li>
        <li>BAGS</li>
        <li>ACCESSORIES</li>
        <li>JEWELRY</li>
        <li>LINGERIE</li>
        <li>BEAUTY</li>
        <li>EDITORIAL</li>
        <li>WHAT TO WEAR</li>
        <li>SALE</li>
    </ul>

    <div class="search  d-flex">
        <p class="mt-3 "  >
        SEARCH</p>
<img width="20px" class="ml-1 mt-1"  src="../assets/search.svg" alt="">
</div>
</div>

<!--navbar ends-->
    </div>
</template>


<script>
export default {
    name:'navbar'
}
</script>


<style scoped>

/* top info */


.menwear .box{
border-right:1px solid white;
height:100%;
}

.box p{
    font-size:0.8rem;
}


.top-grey .info{
    font-style:italic;
}

.top-grey .advice{
font-size:0.7rem;
}
/* site name div*/

.site-name{color:black;}

.site-name h1{
    font-size:2.8rem;
}

.site-name .country p{
  font-size:0.9rem;
  
}

.mini-nav .icon{
    border-right: 1px solid grey;
    border-left: 1px solid grey;
    height:20px;
}


.mini-nav p{
    font-size:0.9rem;
}

/* Top nav */

.top-nav{
background-color:black;
 color:white;
 height:40px;
 font-size:0.8rem;
}

.top-nav ul{
    list-style: none;
    display: flex;

}

.top-nav ul li{
    margin-left:2%;
    margin-top:8px;
}

.top-nav .search{
    background-color:white;
color:black;
}


@media only screen and (max-width:1125px){
    .search p{
        display:none;
    }
}
</style>