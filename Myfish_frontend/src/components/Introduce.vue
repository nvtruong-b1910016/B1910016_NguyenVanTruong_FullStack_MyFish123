<template>
    <div class="wrapper">
       <div class="header">
          <div class="nav-menu">
             <NavMenu />
          </div>
       </div>
       <div class="container">
          <p>
            <h1>WEBSITE QUẢN LÝ BÁN CÁ CẢNH MYFISH</h1>
          </p>
          <p>
            <b><h3 class="h2">Giới thiệu</h3></b>
          </p>
          <p>
            <p class="h3">Thời gian gần đây cùng với sự phát triển của kinh tế xã hội thì nhu cầu giải trí về tinh thần cũng đang rất được quan tâm. Trong số đó bộ môn "Cá cảnh" đang được nhiều người phát động mạnh mẽ, đặt biệt là giới trẻ. Nắm bắt được nhu cầu của thị trường "Website quản lý bán cá cảnh" luôn mang đến những dòng cá khỏe, đẹp, chất lượng sẵn sàng làm hài lòng những vị khách khó tính nhất.</p>
          </p>
          <p>
            <b><p class="h4">MyFish xin cam kết</p></b>
          </p>
          <div class="button">
            <button class="btn btn-success">✔ Luôn đảm bảo về Chất lượng – Số lượng – Đơn giá đúng như những gì được mô tả cho từng sản phẩm trên website MyFish</button>
          </div>
          <div class="button">
            <button class="btn btn-success">✔ Cam kết cá dòng cá đẹp được lai tạo với nguồn gốc xuất xứ rõ ràng, ưu tiên thương hiệu nổi tiếng có nguồn gốc từ Việt Nam</button>
          </div>
          <div class="button">
            <button class="btn btn-success">✔ Khách hàng được kiểm tra hàng thoải mái, MyFish có chính sách bảo hành cho khách hàng cho những trường hợp nhất định</button>
          </div>
          <div class="button">
            <button class="btn btn-success">✔ Giao hàng tận nơi miễn phí cho những đơn hàng từ 2 sản phẩm và trong bán kính 2km, tặng kèm thức ăn và thuốc sát khuẩn</button>
          </div>
          <p>
            <b><p class="h4">👉Chúc Quý khách luôn hài lòng với dịch vụ và những sản phẩm đến từ MyFish!</p></b>
          </p>
          <p>
            <b><p class="h4">👉Trân trọng cảm ơn sự quan tâm của Quý khách hàng!</p></b>
          </p>
          <!-- <p>
             <i class="fa-solid fa-school"></i>
             Trường Công Nghệ Thông Tin Và Truyền Thông
          </p>
          <p>
             <i class="fa-solid fa-envelope icon-email"></i>
             Subin@gmail.com
          </p>
          <p>
             <i class="fa-solid fa-phone icon-phone"></i>
             0794388536
          </p>
         
          <div class="form-group row">
             <label class="col-sm-2 col-form-label">Đóng góp ý kiến</label>
             <div class="col-sm-8">
                <textarea class="form-control" row="7"> </textarea>
                <button
                   type="submit"
                   class="btn btn-primary mt-2 float-left"
                   @click="feedback"
                >
                   Gửi
                </button>
                <button type="reset" class="btn btn-danger mt-2 ml-2 float-left">
                   Xóa
                </button>
                <button class="btn btn-primary">sadasfasfafafasfasfasfasfasfasfasf</button>
             </div>
          </div> -->

    
       </div>
    </div>
 </template>
 
 <script>
 import NavMenu from "../components/NavMenu.vue";
 
 export default {
    components: {
       NavMenu,
    },
    methods: {
       feedback() {
          alert("Cảm ơn bạn đã đóng góp ý kiến!!");
       },
    },
 };
 </script>
 
 <style scoped>
 .wrapper {
    max-width: 100%;
    background-color: #fff;
    font-family: "Open Sans", sans-serif;
    padding-bottom: 50px;
 }
 .header {
    width: 100%;
    height: auto;
 }
 .container {
    text-align: center;
    margin-top: 10px;
    color: #333;
 }
 .h2 {
    text-align:left;
 }
 .h3 {
    text-align:left;
    font-size: 20px;
 }
 .h4 {
    text-align:left;
    font-size: 25px;
 }
 .button {
    text-align:left;
    margin: 10px;
 }
 </style>
 