# Web-Developer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        img{
            border: black solid 2px;
            height: 200px;
            width: 200px;
            padding: none;
            margin: 6px;
            float: left;
            text-align:center;
           font-size: large;
           
        } 
        .title{
            font-size: large; 
            font-family: 'Roboto Slab', serif;

        }
        h6{
            font-size: 13px;
        }
        
    
    table td{
        padding: 5px 10px;
    }
    input, textarea, select{
        border: solid 1px #ddd;
        padding: 5px 20px;
        width: 100%;
    }
    select{
        width: 180px;
    }
    input[type="submit"]{
        width: auto;
        background: red;
        color:#fff;
 
    }
</style>


</head>
<body>
    <h6> Thông tin sinh viên  </h6>
   
   <img src="./382241384_862155721950685_5185576368752940447_n.jpg" alt="">
    <div class="title">
  
     
       <div>
        <h6>Mã Sinh Viên </h6>
        <p>20221719 </p>
       </div>
       <div>
        <h6> Họ tên </h6>
        <p>  Nguyễn Thanh Dũng </p>
       </div>
       <div>
        <h6>Sở thích </h6>
         </div>
         <p> xem phim anime </p>
 </div>
 <hr>
 <h6> Thông tin sinh viên  </h6>

 <img src="./373669037_641227851486501_3709350028107638884_n.jpg" alt="">
  <div class="title">
 
     <div>
      <h6>Mã Sinh Viên </h6>
      <p>20221837 </p>
     </div>
     <div>
      <h6> Họ tên </h6>
      <p>  Phan Thành Long </p>
     </div>
     <div>
      <h6>Sở thích </h6>
       </div>
       <p> pokemon , mèo , xem phim âu mỹ</p>

       <hr>

       <h6> Thông tin sinh viên  </h6>
       <div class="container">
       <img src="./images.jpg" alt="">
        <div class="title">
      
         
           <div>
            <h6>Mã Sinh Viên </h6>
            <p>20221889</p>
           </div>
           <div>
            <h6> Họ tên </h6>
            <p>  Phan Tựu Trường </p>
           </div>
           <div>
            <h6>Sở thích </h6>
             </div>
             <p> Đi Phượt cùng Long</p>
</div>
<hr>
</div>
<h6 class="from data">
    Đơn xin đăng kí làm thành viên 
    
</h6>
<div>
    <!DOCTYPE html><html><head><style>* {  box-sizing: border-box;}input[type=text], select, textarea {  width: 100%;  padding: 12px;  border: 1px solid #ccc;  border-radius: 4px;  resize: vertical;}label {  padding: 12px 12px 12px 0;  display: inline-block;}input[type=submit] {  background-color: #58257b;  color: white;  padding: 12px 20px;  border: none;  border-radius: 4px;  cursor: pointer;  float: right;}input[type=submit]:hover {  background-color: #45a049;}.container {  border-radius: 5px;  background-color: #f2f2f2;  padding: 20px;}.col-25 {  float: left;  width: 25%;  margin-top: 6px;}.col-75 {  float: left;  width: 75%;  margin-top: 6px;}.row:after {  content: "";  display: table;  clear: both;}/* Bố cục linh hoạt: khi màn hình có chiều rộng dưới 600px thì hai cột chồng lên nhau thay vì nằm cạnh nhau */@media screen and (max-width: 600px) {  .col-25, .col-75, input[type=submit] {    width: 100%;    margin-top: 0;}}</style></head><body><div class="container">  <form action="/action_page.php">  <div class="row">    <div class="col-25">      <label for="fname">Họ và tên</label>    </div>    <div class="col-75">      <input type="text" id="fname" name="firstname" placeholder="Tên của bạn">    </div>  </div>  <div class="row">    <div class="col-25">    <label for="country">Quốc gia</label>    </div>    <div class="col-75">      <select id="country" name="country">        <option value="vietnam">Vietnam</option>        <option value="laos">Laos</option>        <option value="cambodia">Cambodia</option>      </select>    </div>  </div>  <div class="row">    <div class="col-25">      <label for="subject">Góp ý</label>    </div>    <div class="col-75">      <textarea id="subject" name="subject" placeholder="Viết gì đó..."       style="height:200px"></textarea>    </div>  </div>  <div class="row">      <input type="submit" value="Xác nhận">  </div>  </form></div></body></html>
</div>
<script src="./project.js"></script>
</body>
</html>
