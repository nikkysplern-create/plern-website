<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plern Everyday Furniture</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Prompt',sans-serif;
}

body{
background:#F8F4EE;
color:#3F3125;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:18px 60px;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(107,79,58,0.92);
backdrop-filter:blur(8px);
z-index:999;
}

.logo{
font-size:28px;
font-weight:700;
color:#fff;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:28px;
font-size:16px;
transition:0.3s;
}

nav a:hover{
opacity:0.7;
}

.hero{
height:100vh;
background:url('banner.jpg') center/cover no-repeat;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.overlay{
background:rgba(0,0,0,0.35);
padding:50px;
border-radius:18px;
color:white;
max-width:800px;
animation:fadeUp 1s ease;
}

.hero h1{
font-size:64px;
margin-bottom:15px;
line-height:1.2;
}

.hero p{
font-size:22px;
margin-bottom:30px;
font-weight:300;
}

.btn{
display:inline-block;
padding:14px 34px;
background:#E8DCCB;
color:#3F3125;
border-radius:10px;
text-decoration:none;
font-weight:600;
transition:0.3s;
}

.btn:hover{
transform:translateY(-3px);
}

section{
padding:90px 60px;
}

.title{
text-align:center;
font-size:42px;
margin-bottom:50px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(270px,1fr));
gap:28px;
}

.card{
background:white;
border-radius:18px;
overflow:hidden;
box-shadow:0 8px 22px rgba(0,0,0,0.08);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:260px;
object-fit:cover;
}

.card-content{
padding:22px;
}

.card h3{
font-size:24px;
margin-bottom:10px;
}

.price{
font-size:22px;
font-weight:700;
color:#6B4F3A;
margin-top:12px;
}

.about{
max-width:850px;
margin:auto;
text-align:center;
font-size:22px;
line-height:1.8;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
margin-top:40px;
}

.feature{
background:white;
padding:25px;
border-radius:16px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,0.05);
}

.contact{
text-align:center;
font-size:22px;
line-height:2;
}

.line-btn{
display:inline-block;
margin-top:20px;
background:#7A8450;
color:white;
padding:14px 30px;
border-radius:12px;
text-decoration:none;
}

footer{
background:#6B4F3A;
color:white;
text-align:center;
padding:25px;
}

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(40px);
}
to{
opacity:1;
transform:translateY(0);
}
}

@media(max-width:768px){

header{
padding:15px 20px;
}

nav{
display:none;
}

.hero h1{
font-size:40px;
}

.hero p{
font-size:18px;
}

section{
padding:70px 20px;
}

.title{
font-size:32px;
}

}
</style>
</head>

<body>

<header>
<div class="logo">Plern</div>
<nav>
<a href="#home">หน้าแรก</a>
<a href="#products">สินค้า</a>
<a href="#about">เกี่ยวกับเรา</a>
<a href="#contact">ติดต่อ</a>
</nav>
</header>

<section class="hero" id="home">
<div class="overlay">
<h1>Make Home Feel Better</h1>
<p>เฟอร์นิเจอร์อบอุ่นสำหรับทุกวัน สไตล์มินิมอล Earth Tone</p>
<a href="#products" class="btn">ดูสินค้า</a>
</div>
</section>

<section id="products">
<h2 class="title">สินค้าแนะนำ</h2>

<div class="products">

<div class="card">
<img src="product1.jpg">
<div class="card-content">
<h3>ชื่อสินค้า</h3>
<p>ใส่รายละเอียดสินค้า</p>
<div class="price">฿0</div>
</div>
</div>

<div class="card">
<img src="product2.jpg">
<div class="card-content">
<h3>ชื่อสินค้า</h3>
<p>ใส่รายละเอียดสินค้า</p>
<div class="price">฿0</div>
</div>
</div>

<div class="card">
<img src="product3.jpg">
<div class="card-content">
<h3>ชื่อสินค้า</h3>
<p>ใส่รายละเอียดสินค้า</p>
<div class="price">฿0</div>
</div>
</div>

<div class="card">
<img src="product4.jpg">
<div class="card-content">
<h3>ชื่อสินค้า</h3>
<p>ใส่รายละเอียดสินค้า</p>
<div class="price">฿0</div>
</div>
</div>

</div>
</section>

<section id="about">
<h2 class="title">เกี่ยวกับเรา</h2>
<div class="about">
Plern Everyday Furniture คือร้านเฟอร์นิเจอร์ที่ออกแบบเพื่อการใช้ชีวิตจริง  
เรียบง่าย อบอุ่น เข้ากับทุกบ้าน และใช้งานได้ทุกวัน
</div>

<div class="features">
<div class="feature">วัสดุคุณภาพดี</div>
<div class="feature">ดีไซน์มินิมอล</div>
<div class="feature">ส่งทั่วประเทศ</div>
<div class="feature">บริการเป็นกันเอง</div>
</div>
</section>

<section id="contact">
<h2 class="title">ติดต่อเรา</h2>
<div class="contact">
LINE : @yourline <br>
Facebook : Plern Everyday Furniture <br>
Instagram : @plern.everyday
<br>
<a href="#" class="line-btn">แชทสั่งซื้อ</a>
</div>
</section>

<footer>
© 2026 Plern Everyday Furniture
</footer>

</body>
</html>
