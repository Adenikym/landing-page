<template>
    <div class="wrapper col-lg-12 px-0 py-2 d-flex">
<div class="useful col-lg-5 text-left ml-4 ">
    <h2>USEFUL INFORMATION</h2>
<div class="lists col-lg-10 d-flex mt-3">

    <ul class="col-lg-4">
        <li>Lorem.</li>
        <li>Lorem.</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        
    </ul>

    <ul class="col-lg-4">
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
    </ul>
</div>
<p style="color:pink" class="ml-3">&copy; 2021 <span>STYLEEST</span></p>
</div>

<div class="contact col-lg-6">
    <h2>STAY IN TOUCH</h2>

 <div class="details col-lg-12 d-flex">
     <p class="mt-4">Our Apps</p>

     <div class="form-group col-lg-7 mt-3">
        <input type="text" class="form-control col-lg-12" placeholder="Subscribe to styleest newsletters" >
     </div>
 </div>
</div>


    </div>
</template>



<script>
export default {
    name:'bottomnav'
}
</script>



<style scoped>
.wrapper{
    background: black;
    color:white;
   
}

.wrapper h2{
    font-size: 1rem;
    margin-top:20px ;
}

.form-control{
     border:1px solid pink;
     background: black;
     color:white;
}

.useful ul{
    list-style: none;
}
</style>