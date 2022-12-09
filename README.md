# Fitness-Website
# CSS Source code

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>FITNESS WEBSITE</title>
	
</head>
<body>
	<style>
		@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
:root{
	--primary-color: #050505;
	--secondary-color: #feffff;
	--font: 'Poppins', sans-serif;
}
*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
}
.btn{
	padding: .6rem .8rem;
	text-transform: uppercase;
	font-family: var(--font);
	background: var(--primary-color);
	color: white;
	font-size: 16px;
	text-decoration: none;
	outline: none;
	border: 2px solid var(--primary-color);
	transition: .3s;
	cursor: pointer;
}
.btn:hover{
	background: transparent;
}
body{
	background: black;
	font-family: var(--font);
}

nav{
	position: fixed;
	width: 100vw;
	height: 60px;
	border-top: .5rem solid var(--primary-color);
	display: flex;
	justify-content: space-between;
	align-items: center;
	z-index: 999999;
}

.logo{
	display: flex;
	justify-content: center;
	align-items: center;
	height: 55px;
	width: 15%;
	font-weight: 700;
	background: var(--primary-color);
}

.logo::before{
	content: "Get";
	color:red;
}
.logo::after{
	content: "Fit";
	color:white;
}

ul{
	display: flex;
	align-items: center;
	height: 60px;
}

ul a{
	text-decoration: none;
	color: white;
	margin: 0 2rem;
	text-transform: uppercase;
	font-family: var(--font);
	font-weight: 700;
	font-size: 16px;
}
ul li{
	list-style: none;
}
ul a:hover{
	color: var(--primary-color);
}

.banner{
	background: url("img/banner2.jpg");
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	background-attachment: fixed;
	height: 85vh;
}

.intro{
	position: absolute;
	top: 30%;
	left: 10%;
	color: white;
}

.intro h2,p{
	display: block;
	width: 60%;
}

.intro h2{
	text-transform: uppercase;
	letter-spacing: 2px;
	font-size: 30px;
}
.intro .btn{
	margin-top: 2rem;
}

.row{
	display: flex;
	justify-content: center;
}
.card{
	width: 33.3%;
	height: 250px;
	display: flex;
	justify-content: center;
	flex-direction: column;
	align-items: center;
}
.card h2{
	text-transform: uppercase;
}


	</style>
	<header>
		<nav>
			<h2 class="logo"></h2>
			<ul>
				<a href="#"><li>Home</li></a>
				<a href="C:\Users\hp pc\Downloads\gym\gym\About Page.html"><li>About</li></a>
				<a href="#"><li>Activities</li></a>
				<a href="#"><li>Performances</li></a>
				<a type="text" onclick="alert('Contact Us: getfit456@gmail.com   , lovely professional university, phagwara punjab, 144411   9146598372, 9985625425')"><li>Contact</li></a>
			</ul>
		</nav>
		<div class="banner">
			<div class="intro">
				<h1>FIT AT HOME</h1>
				<br>
				<p>No need to go to gym, when you can be fit at Home.</p>
				<button class="btn">Start From Today</button>
			</div>
		</div>
	</header>
	<div class="row">
		<div class="card" style="color: white; background: var(--primary-color);">
			<a href="C:\Users\hp pc\Downloads\gym\gym\fitness website jogging.html">
			<h2>BEGINNER</h2>
		</a>
			<p></p>
			
		</div>
		<div class="card" style="background: white;">
			<a href="fitness website burpee.html">
			<h2 style="color: var(--primary-color);">INTERMEDIATE</h2>
		</a>
			<p style="color: var(--secondary-color);"></p>
			
		</div>
		<a href="fitness website plank.html">
		<div class="card" style="color: white;background: var(--primary-color);">
			<h2>
				
				ADVANCE
			
			</h2>
		</a>
			<p></p>
			
		</div>
	</div>
	<hr><h1><font color="white">
		<center>
			CONTACT DETAILS
		</center>
		</font></h1><hr>
	<h2>
	<center><font color="white">
<p>Contact Us: getfit456@gmail.com
	<br>
	lovely professional university, phagwara
	<br>
	punjab, 144411
	<br>
	9176854896, 9976345678
</p>
</font></center>
</h2>
</body>
</html>
