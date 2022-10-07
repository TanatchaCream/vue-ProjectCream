<template>
    <div>
       <navbar />
       <section class="home">
   
   <div class="image">
       <img src="images/profile.png" alt="">
   </div>
   
   <div class="content">
       <h3>I'm Tanatcha Buratakan</h3>
       <span>"ทำวันนี้ให้ดีที่สุด"</span>
       <p>ปัจจุบันเป็นนักศึกษาชั้นปีที่2ในคณะวิศวกรรมศาสตร์สาขามัลติมีเดียและเอนเตอร์เทนเม้น มหาวิทยาลัยกรุงเทพ</p>
       <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
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