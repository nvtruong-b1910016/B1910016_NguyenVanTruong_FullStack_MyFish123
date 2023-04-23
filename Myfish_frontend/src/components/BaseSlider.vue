<template>
    <div class="slider-box">
       <div class="slider-content">
          <Splide :options="options" aria-label="My Favorite Images">
             <SplideSlide>
                <img src="../images/cac-loai-ca-canh-dep-nhat-the-gioi.webp" alt="Sample 2" />
                <div class="content">
                   <a href="#"
                      >Cá BETTA xanh đen thuần chủng Thái Lan
                      </a>
                </div>
             </SplideSlide>
             <SplideSlide>
                <img src="../images/anh-ca-canh-dep-nhat-1.webp" alt="Sample 1" />
                <div class="content">
                   <a href="#"
                      >Cá Koi lai nhật size mini đỏ trắng ánh kim</a
                   >
                </div>
             </SplideSlide>
             <SplideSlide>
                <img src="../images/Screenshot 2023-04-11 193909.png" alt="Sample 2" />
                <div class="content">
                   <a href="#"
                      >Cá Dĩa lai, thuần chủng đủ các chủng loại</a
                   >
                </div>
             </SplideSlide>
             <SplideSlide>
                <img src="../images/ca-canhhh_1672977312.jpg" alt="Sample 2" />
             </SplideSlide>
             <SplideSlide>
                <img src="../images/ta-con-ca-vang-dang-boi-trong-be-ca-1.jpg" alt="Sample 2" />
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
          rewind: true,
          gap: "1rem",
          autoplay: true,
       };
 
       return { options };
    },
 });
 </script>
 
 <style scoped>
 .splide__slide img {
    width: 100%;
    height: 300px;
    object-fit: cover; /* Bao phủ toàn bộ khung hình */
    display: block;
 }
 .content {
    margin-top: 5px;
    position: absolute; /* Để đưa nội dung vào trong khung ảnh */
    right: 10px;
    bottom: 20px;
    width: 400px;
    text-align: justify;
    background-color: #333;
    padding: 7px 7px 12px;
    border-radius: 3px;
    opacity: 0.85;
 }
 .content a {
    text-decoration: none;
    color: white;
    display: inline-block;
    line-height: 24px;
    text-transform: uppercase;
 }
 </style>
 