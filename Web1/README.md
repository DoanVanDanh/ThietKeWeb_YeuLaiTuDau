# ThietKeWeb_YeuLaiTuDau

<a href="https://www.w3schools.com/w3css/tryw3css_templates_blog.htm">link mẫu</a>

++<b></b>: bôi đậm : ngoài cách dùng :font-weight: bold
++ con : width:100% ==> tương đối so với cha nó
<img src="img/woods.jpg" class="col-12" alt="" > <!-- class="col-12":width: 100% so với cha <div class="entry"></div> -->

++ căn giữa phần header 
header {
    text-align: center;
}


-- animation:
++ tạo hiệu ứng nổi có viền mờ mờ 
box-shadow: 0 4px 10px 0 rgba(0,0,0,0.2), 0 4px 20px 0 rgba(0,0,0,0.19); 
++  hiệu ứng nổi(k viền) 
box-shadow: 0 2px 5px 0 rgba(0,0,0,0.16), 0 2px 10px 0 rgba(0,0,0,0.12);


-- 2 thẻ div cạnh nhau==> mún nó nổi cạnh nhau?????
++div trái: float:left  
++div phải: float:right
===================================
#h1 Responsive
/*
response web (tự động thay đổi tùy theo kích thước màn hình_thiết bị(desktop hay mobile)
*/
/* For desktop: */
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}

@media only screen and (max-width: 768px) {
   /* For mobile phones: */
   [class*="col-"] {
       width: 100%;
   }
}
/* ending responsive */