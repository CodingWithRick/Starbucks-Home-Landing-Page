<!DOCTYPE html>
<html>
<head>
	<title>Starbucks Home Landing Page</title>
	<style type="text/css">
		@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
		*{
			font-family: "Poppins", sans-serif;
			overflow: hidden;
		}
		.flex{
			display: flex;
			flex-direction: row;
			align-items: center;
			justify-content: center;
			width: 100vw;
			box-shadow: 0px 10px 50px rgb(146, 148, 156);
		}
		.flex img{
			max-width: 80px;
			margin: 10px;
		}
		.flex h2{
			margin: 10px;
			font-weight: 100;
			display: flex;
		}
		.flex h2 div{
			font-weight: 1000 !important;
			color: #017143;
			margin-right: 5px;
		}
		h4{
			font-size: 20px;
			margin: 50px 660px;
			text-decoration: underline;
			color: #aaa;
			text-shadow: 1px 1px #000;
			width: 150px;
		}
		h6{
			font-stretch: 15px;
			margin: 50px 450px;
			text-align: justify;
		}
		h6 ul li a{
			color: cyan;
			font-size: 16px;
			text-shadow: 1px 1px darkcyan;

		}
		button{
			margin-left: 43.5%;
			background: linear-gradient(90deg, rgba(0,104,255,1) 0%, rgba(222,0,255,1) 100%);
			border: none;
			outline: none;
			color: #fff;
			border-radius: 2px;
			width: 200px;
			height: 30px;
			text-decoration: none;
			font-family: cursive !important;
			cursor: pointer;
		}
		button:focus{
			border: 1px solid #000;
		}
	</style>
</head>
<body>
	<div class="flex">
		<img src="logo.png">
		<h2><div>Starbucks</div> Home Landing Page</h2>
	</div>
<h4>
	AIMS
</h4>
<h6>
	<ul>
		<li>Creating A Navbar - <a>DONE</a></li>
		<li>Creating A Circle at the Corner - <a>DONE</a></li>
		<li>Displaying Image of the Product - <a>DONE</a></li>
		<li>Adding Information - <a>DONE</a></li>
		<li>Adding Social Media Icons - <a>DONE</a></li>
		<li>Adding Thumbs - <a>DONE</a></li>
		<li>Image and Circle Color Changing Functionality Using JavaScript - <a>DONE</a></li>
	</ul>
</h6>
<button><a>Subscribe To My Channel</a></button>
</body>
</html>