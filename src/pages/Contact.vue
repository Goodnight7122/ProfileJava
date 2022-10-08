<template>

    <div>
       <navbar />
       <section class="Contact">
   
        <h1 class="heading">Con<span>tact</span> </h1>

        <div class="Contactcon">

            <form action="">

        <div class="inputBox">
            <input type="text" placeholder="your name">
            <input type="number" placeholder="your number">
        </div>

        <div class="inputBox">
            <input type="email" placeholder="your email">
            <input type="text" placeholder="your subject">
        </div>

        <textarea name="" placeholder="your message" id="" cols="30" rows="10"></textarea>

        <input type="submit" value="send message" class="btn">

    </form>

<div class="box">
    <i class="fas fa-phone"></i>
                <div class="info">
                    <h3>number :</h3>
                    <p>+66653242552</p>
                </div>
</div>


</div>

   
   </section>
    </div>
   </template>
   
   <script>
   import Navbar from '../components/Navbar.vue';
   export default {
       components: { Navbar }
   }
   </script>
   
   <style>
   
   </style>