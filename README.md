# noomie-movie
A website created for all movie and drama 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KDrama Hub</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:linear-gradient(to right,#ff416c,#ff4b2b);
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:30px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:yellow;
}

.hero{
    height:75vh;
    background:url("https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?auto=format&fit=crop&w=1600&q=80") center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h1{
    font-size:55px;
}

.hero p{
    margin:20px 0;
    font-size:18px;
}

.hero button{
    padding:15px 35px;
    border:none;
    background:#ff416c;
    color:white;
    font-size:18px;
    border-radius:30px;
    cursor:pointer;
}

.hero button:hover{
    background:#ff4b2b;
}

.container{
    width:90%;
    margin:auto;
    padding:50px 0;
}

h2{
    margin-bottom:30px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.card{
    background:#222;
    border-radius:15px;
    overflow:hidden;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#ccc;
    font-size:14px;
}

footer{
    text-align:center;
    background:#000;
    padding:20px;
    color:#aaa;
}
</style>

</head>
<body>

<header>
<div class="logo">KDrama Hub</div>

<nav>
<a href="#">Home</a>
<a href="#">K-Dramas</a>
<a href="#">Variety Shows</a>
<a href="#">Movies</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<div>
<h1>Watch Korean Entertainment</h1>
<p>Discover the best Korean dramas, variety shows, and movies.</p>
<button>Browse Now</button>
</div>
</section>

<div class="container">

<h2>Popular Shows</h2>

<div class="grid">

<div class="card">
<img <img src="images/running-man.jpg" alt="Running Man">
<div class="card-content">
<h3>Running Man</h3>
<p>Legendary Korean variety show full of games, missions and comedy.</p>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/300/400?random=1" alt="">
<div class="card-content">
<h3>Queen of Tears</h3>
<p>Romantic drama starring Kim Soo-hyun and Kim Ji-won.</p>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/300/400?random=2" alt="">
<div class="card-content">
<h3>Crash Landing on You</h3>
<p>A famous love story between a South Korean heiress and a North Korean officer.</p>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/300/400?random=3" alt="">
<div class="card-content">
<h3>Business Proposal</h3>
<p>A romantic comedy loved by fans around the world.</p>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/300/400?random=4" alt="">
<div class="card-content">
<h3>Moving</h3>
<p>Superpowered students and parents protect their secrets.</p>
</div>
</div>

<div class="card">
<img src="https://picsum.photos/300/400?random=5" alt="">
<div class="card-content">
<h3>The Glory</h3>
<p>A revenge drama with an unforgettable story.</p>
</div>
</div>

</div>

</div>

<footer>
© 2026 KDrama Hub | Made with ❤️
</footer>

</body>
</html>
