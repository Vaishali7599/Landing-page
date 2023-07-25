<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Perfect hotel</title>
	<script src="https://kit.fontawesome.com/a076d05399.js"></script>
	<style>
		body{
			font-family:"Secular One script=latin rev=1";
			margin:0px;
			padding:0px;
			background: url("https://images.pexels.com/photos/3201765/pexels-photo-3201765.jpeg?crop=entropy&cs=srgb&dl=pexels-andrew-neel-3201765.jpg&fit=crop&fm=jpg&h=3714&w=5570") no-repeat;
			background-size: 1345px;
			}
		.btn{
			position: absolute;
			top: 27%;
			right: 3%;
				/* border: 2PX solid red; */
				
		}
		.submit :hover{
			background-color: black;
			color: aliceblue;
		}
		
		
		.left{
			display: inline-block;
			top: 0px;
			position: absolute;
			left: 20px;
		}
		.mid{
			display: block;
			width: 60%;
			margin: 12px auto;
			color: red;
			}
		.right{
			position: absolute;
			right:50px;
			top:5px;
			display: inline-block;	
			}
		
		
		.right input{
			height: 30px;
		}
		.navbar{
			display:inline-block;
			}
		.navbar li{
			display:inline-block;
			font-size: 25px;
			}
		
		.navbar li a{
			display: block;
			height: 100%;
			width: 100%;
			line-height: 40px;
			color:black;
			padding-left: 40px;
			text-decoration: none;
			}
		 .navbar li a:hover, .navbar li active{
			text-decoration: underline;
			color: red;
			}
		.main{
			margin:3px auto;
			padding:10px;
			width: 500px;
			border-radius:20px;
			cursor:pointer;
			font-size:20px;
			border-radius:8px;
			color:black;
			font-family:'Baloo Bhai', cursive;
			text-align:center;
			display:block;
			font-size: 25px;
			/* border: 2px solid black; */
			background-color: #ffffff40;
			}
		.down{
			text-decoration:underline;
			font-size:28px;
			color:black;
			
			text-align:center;
			margin:3px auto;
			padding:0px;
			width:500px;
			font-size: 30px;
			
			}
		.like{
			color:white;
		}
	
	</style>

</head>
<body>
	<header class ="header">
		<div class="left">
		</div>
	<header class ="header">
		<div class="mid">
			<ul class="navbar">
				
				<li><a href="about.html"><i class="fas fa-question-circle"></i>About</a></li>
				<li><a href="Services.html"><i class="fas fa-sliders-h"></i>Services</a></li>
				<li><a href="#"><i class="fas fa-envelope"></i>Contact us</a></li>
				<li><a href="#"><i class="fas fa-bars"></i>More</a></li>
			</ul>
		</div>
		<div class="right">
			<form action="https://www.google.com/search" method="GET">
				<input type="text" name="q" placeholder="Search">
			</form>
			<div class="btn">
				<a href="#"><i class="fas fa-search"></i></a>
			</div>
		</div>
	</header>
		<div class="main">
		<h2>BEST PLACE TO STAY, FEELS LIKE HOME!!</h2>
		<div class=form-group>
			Gender:Male <input type ="radio" name="myGender"> Female <input type= "radio" name="myGender">
			other <input type ="radio" name="myGender">
			</div>
			<div class=form-group>
				<input type="text" name=" " placeholder="Enter your name">
			</div>
			<div class=form-group>
				<input type="text" name=" " placeholder="Enter your age">
			</div>
			<div class=form-group>
				<input type="text" name=" " placeholder="Enter your contact number">
			</div>
			<div class="submit">
			<input type ="submit" value="Submit now">
			</div>
			
		<div class="down">
		<h3>WELCOME ALWAYS</h3>
		
		</div>
		
</body>
</html>
