<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vedant Medical - Products</title>

<style>
body{
    font-family:Arial,sans-serif;
    margin:0;
    background:#f4f4f4;
}
header{
    background:#d60000;
    color:white;
    text-align:center;
    padding:20px;
}
.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    padding:20px;
}
.card{
    background:white;
    border-radius:10px;
    box-shadow:0 2px 8px rgba(0,0,0,.2);
    text-align:center;
    padding:15px;
}
.card img{
    width:100%;
    height:180px;
    object-fit:cover;
    border-radius:8px;
}
.card h3{
    color:#d60000;
}
button{
    background:#d60000;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:5px;
    cursor:pointer;
}
button:hover{
    background:#000;
}
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
<h1>Vedant Medical</h1>
<p>Modakpur, Begamganj–Sultanganj Road, Raisen (MP)</p>
<p>📞 7974841935</p>
</header>

<section class="products">

<div class="card">
<img src="https://via.placeholder.com/300x180?text=Tablets" alt="Tablets">
<h3>Tablets</h3>
<p>All types of tablets available.</p>
<button>Call Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x180?text=Syrups" alt="Syrups">
<h3>Syrups</h3>
<p>Quality syrups for all age groups.</p>
<button>Call Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x180?text=Baby+Care" alt="Baby Care">
<h3>Baby Care</h3>
<p>Baby food, diapers and healthcare products.</p>
<button>Call Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x180?text=First+Aid" alt="First Aid">
<h3>First Aid</h3>
<p>Bandages, antiseptics and emergency care items.</p>
<button>Call Now</button>
</div>

</section>

<footer>
© 2026 Vedant Medical | WhatsApp: 7974841935
</footer>

</body>
</html>
