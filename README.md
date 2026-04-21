<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>التوعية بالهندسة الاجتماعية</title>

<style>
body{
font-family: Arial, sans-serif;
direction: rtl;
margin:0;
background:#f5f7fb;
line-height:1.7;
}

/* الهيدر */
header{
background:linear-gradient(90deg,#0d6efd,#0a58ca);
color:white;
padding:30px 15px;
text-align:center;
}

/* القائمة */
nav{
background:#111;
display:flex;
justify-content:center;
flex-wrap:wrap;
padding:10px;
position:sticky;
top:0;
z-index:1000;
}

nav a{
color:white;
margin:5px 10px;
text-decoration:none;
font-weight:bold;
padding:8px 12px;
border-radius:5px;
}

nav a:hover{
background:#0d6efd;
}

/* المحتوى */
.container{
padding:15px;
max-width:1000px;
margin:auto;
}

.card{
background:white;
padding:15px;
margin-bottom:20px;
border-radius:12px;
box-shadow:0 0 10px rgba(0,0,0,0.08);
}

.card img{
width:100%;
height:auto;
border-radius:10px;
margin-bottom:10px;
display:block;
}

h2{
color:#0d6efd;
}

/* زر */
button{
background:#0d6efd;
color:white;
border:none;
padding:10px 15px;
border-radius:6px;
cursor:pointer;
margin-top:10px;
width:100%;
font-size:16px;
}

button:hover{
background:#0a58ca;
}

/* الفوتر */
footer{
background:#111;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}

/* 📱 تحسين الجوال */
@media (max-width:768px){
header h1{
font-size:22px;
}

nav a{
font-size:14px;
}

.card{
padding:12px;
}

h2{
font-size:18px;
}
}
</style>
</head>

<body>

<header id="home">
<h1>التوعية بالهندسة الاجتماعية</h1>
<p>احمِ نفسك من محاولات الاحتيال الإلكتروني</p>
</header>

<nav>
<a href="#home">الرئيسية</a>
<a href="#types">أنواع الهجمات</a>
<a href="#protection">الحماية</a>
<a href="#contact">تواصل</a>
</nav>

<div class="container">

<!-- تعريف -->
<div class="card">
<img src="https://images.unsplash.com/photo-1563986768609-322da13575f3" loading="lazy" alt="social engineering">
<h2>ما هي الهندسة الاجتماعية؟</h2>
<p>
هي أسلوب خداع يستخدمه المهاجم للحصول على معلومات حساسة مثل كلمة المرور أو رمز التحقق من خلال التلاعب بالمستخدم.
</p>
</div>

<!-- الأنواع -->
<div class="card" id="types">
<img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b" loading="lazy" alt="cyber attack">
<h2>أنواع الهجمات</h2>
<ul>
<li>التصيد الاحتيالي Phishing</li>
<li>انتحال الهوية</li>
<li>روابط مزيفة</li>
<li>رسائل SMS احتيالية</li>
<li>مكالمات مزيفة</li>
</ul>
</div>

<!-- الحماية -->
<div class="card" id="protection">
<img src="https://images.unsplash.com/photo-1510511459019-5dda7724fd87" loading="lazy" alt="security">
<h2>كيف تحمي نفسك؟</h2>
<ul>
<li>لا تضغط روابط مجهولة</li>
<li>تحقق من المرسل</li>
<li>لا تشارك كلمة المرور</li>
<li>فعّل التحقق الثنائي</li>
<li>بلّغ عن الرسائل المشبوهة</li>
</ul>

<button onclick="alert('أحسنت! تذكر لا تشارك معلوماتك أبداً')">
نصيحة أمنية
</button>
</div>

</div>

<footer id="contact">
<p>مشروع توعوي بالأمن السيبراني - Social Engineering Awareness</p>
</footer>

</body>
</html>
