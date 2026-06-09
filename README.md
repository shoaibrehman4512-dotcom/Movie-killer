
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Movie Killer</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Arial,sans-serif;background:#141414;color:white}
header{
background:#e50914;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}
.logo{font-size:28px;font-weight:bold}
.search{
padding:10px;
width:250px;
border:none;
border-radius:5px;
}
.hero{
text-align:center;
padding:60px 20px;
background:#222;
}
.hero h1{font-size:50px}
.hero p{margin-top:10px}
.movies{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:30px;
}
.card{
background:#222;
width:220px;
border-radius:10px;
overflow:hidden;
}
.card img{
width:100%;
height:300px;
object-fit:cover;
}
.card h3{
padding:10px;
text-align:center;
}
.card p{
padding:0 10px 10px;
font-size:14px;
text-align:center;
}
footer{
background:#000;
text-align:center;
padding:20px;
margin-top:20px;
}
</style>
</head>
<body>

<header>
<div class="logo">🎬 Movie Killer</div>
<input class="search" type="text" placeholder="Search Movies">
</header>

<section class="hero">
<h1>Welcome to Movie Killer</h1>
<p>Latest Movie Information & Reviews</p>
</section>

<section class="movies">

<div class="card">
<img src="https://via.placeholder.com/220x300" alt="Movie">
<h3>Movie 1</h3>
<p>Movie description here.</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/220x300" alt="Movie">
<h3>Movie 2</h3>
<p>Movie description here.</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/220x300" alt="Movie">
<h3>Movie 3</h3>
<p>Movie description here.</p>
</div>

</section>

<footer>
© 2026 Movie Killer
</footer>

</body>
</html>