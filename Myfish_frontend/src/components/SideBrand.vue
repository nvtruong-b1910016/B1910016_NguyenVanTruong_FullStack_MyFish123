<template>
    <div class="container">
       <div class="box-container">
          <h3 class="title">Thương hiệu nổi bật</h3>
          <Splide :options="options" aria-label="My Favorite Images">
             <SplideSlide>
                <img src="../images/brands/logo1.png" alt="Thương hiệu 1" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo2.png" alt="Thương hiệu 2" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo3.png" alt="Thương hiệu 3" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo4.png" alt="Thương hiệu 4" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo5.png" alt="Thương hiệu 5" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo6.png" alt="Thương hiệu 6" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo7.png" alt="Thương hiệu 7" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo8.png" alt="Thương hiệu 8" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/brands/logo9.png" alt="Thương hiệu 9" />
             </SplideSlide>
          </Splide>
       </div>
    </div>
 </template>
 
 <script>
 import { Splide, SplideSlide } from "@splidejs/vue-splide";
 import { defineComponent } from "vue";
 
 export default defineComponent({
    components: {
       Splide,
       SplideSlide,
    },
    setup() {
       const options = {
          perPage: 6,
          perMove: 1,
          gap: 2,
          height: 160,
          rewind: true,
          autoplay: true,
       };
 
       return { options };
    },
 });
 </script>
 
 <style scoped>
 .container {
    margin: 0 auto;
 }
 .box-container {
    height: 150px;
    padding: 0 0;
 }
 .title {
    font-size: 26px;
    font-weight: normal;
    border-bottom: 3px solid #eee;
    margin-bottom: 30px;
    padding: 10px 0;
 }
 .splide__slide {
    height: 45px !important;
    text-align: center;
 }
 </style>
 