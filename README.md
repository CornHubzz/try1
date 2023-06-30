<!DOCTYPE html>
<html>
	<head> 
		<title>Dog Supplies</title>
		<style>
		@import url('https://fonts.cdnfonts.com/css/church-street');
		@import url('https://fonts.cdnfonts.com/css/illuminoust');

			.upper {
				z-index: 1;
				width: 99.5%;
				height: 30%;
				background-image: url(bannerz.png);
				background-repeat: no-repeat;
				background-size: 100% 100%;
				 background-position: center; 
			}
			.lower {
				z-index: 0;
				width: 98.67%;
				height: 125%;
				background-color: #D9D9D9;
				margin-left: auto;
				margin-right: auto;
				display: block;
				position: absolute;
			}
			.container {
				margin-top: 3%;
				position: relative;
				width: 100%;
				height: 23%;
				align-content: center;
				display: inline-block;
			}
			.box:hover {
				width: 15%;
				height: 100%;
				transform: scale(1.1,1.1);
				box-shadow: 0 5px 15px #385c54;
				background-color: #385c54;
				color: white;
			}
			.button:hover {
				color: white;
				font-size: 25px;
				box-shadow: 0 5px 15px #385c54;
				background-color: #385c54;
				transform: scale(1.1,1.1);
			}
			.box {
				display: inline-block;
				position: relative;
				width: 15%;
				height: 100%;
				background-color: white;
				margin-left: 1.3%;
				box-shadow: 5px 5px 10px #888888;
				transition: width 0.5s, height 0.5s, transform 0.5s;
				transition-timing-function: ease;
			}
			.img {
				width: 70%;
				height: 70%;
				margin: auto;
				display: flex;
				align-items: center;
				justify-content: center;
			}
			.item {
				position: absolute;	
				text-align: center;
				margin-left: 15%;
				margin-top: 5%;
				font-size: 20px;
				font-family: 'Church Street', sans-serif;
				font-weight: bold;
			}
			.price {
			    position: absolute;	
				text-align: center;
				margin-left: 15%;
				margin-top: 17%;
				font-size: 20px;
				font-weight: 900;
				font-family: 'illuminoust', sans-serif;
				letter-spacing: 3px;
			}
			.hel {
			    position: absolute;	
				text-align: left;
				margin-left: 1%;
				margin-top: 0%;
				font-size: 20px;
				font-weight: 900;
				font-family: 'Church Street', sans-serif;
				letter-spacing: 1.5px;
				line-height: 39px;
				width: 60%;
			}
			.gg {
				width: 20%;
				height: 90%;
				margin-left: 65%;
				margin-top: 0%;
			
			}
			.dog2 {
				width: 20%;
				height: 150%;
				margin-left: 0%;
				margin-top: -3%;
				position: absolute;	
			
			}
			.button {
				position: absolute;
				background-color: white;
				border: none;
				color: #385c54;
				font-family: 'TT Ricordi Greto Trial Variable', sans-serif;
				width: 10%;
				padding: 15px 32px;
				text-align: center;
				text-decoration: none;
				font-size: 20px;
				margin-top: 2%;
				margin-left: 43%;
				cursor: pointer;
				transition: all 0.2s ease-in-out;
			}
		</style>
	</head>
	<body>
	<div class="upper">
	</div>
	
	<div class="lower">
		<div class="container"> 
			<p class="hel"> 
			
			Pet's Paradise is a premier destination for all your pet supply needs. We cater to pet owners who prioritize the health, happiness, and well-being of their beloved furry friends. Our business offers a wide range of high-quality pet supplies, including food, toys, grooming products, accessories, and more. We strive to create a paradise-like experience for both pets and their owners, providing a one-stop shop for all their requirements. Our knowledgeable and friendly staff are passionate about animals and are always ready to assist customers in finding the perfect products for their pets.
		
			</p>
			<iframe class="gg" width="560" height="315" src="https://www.youtube.com/embed/2nRuiZbb1D8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
			<img src="o.png" class="dog2"> </img>
		</div>
		
		<div class="container"> 
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/a2/50/d6/a250d6cac1e8a050b7adcdfbb04e6835.jpg"> </img>
				<p class="item">Food Bowl</p>
				<p class="price">Php 300.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/7e/4f/e4/7e4fe4be23ff9247e4e55bd115e31d8f.jpg"> </img>
				<p class="item">Dog Leash</p>
				<p class="price">Php 150.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/db/65/1b/db651becf2f14eaba15aa88cb2de1da6.jpg"> </img>
				<p class="item">Dog Soap</p>
				<p class="price">Php 200.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/9e/a4/05/9ea4052dc0b484fa3d740116621fca4d.jpg"> </img>
				<p class="item">Cat Soap</p>
				<p class="price">Php 200.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/eb/0e/a6/eb0ea632ade176875a11671b78fe305a.jpg"> </img>
				<p class="item">Treats</p>
				<p class="price">Php 400.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/9f/b2/86/9fb2864f44f60030b17fa7bba234a48d.jpg"> </img>
				<p class="item">Snacks</p>
				<p class="price">Php 300.00</p>
			</div>
		</div>
		
		
		<div class="container"> 
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/6e/31/90/6e3190043c590d18b52010c3eff89ccd.jpg"> </img>
				<p class="item">Dog Treats</p>
				<p class="price">Php 300.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/3b/e0/1d/3be01d16b7ca03e2a0e0103e7068d81b.jpg"> </img>
				<p class="item">Dog/Cat Food</p>
				<p class="price">Php 200.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/86/79/43/867943293ab18e9fd39c9aec81bcbe64.jpg"> </img>
				<p class="item">Dog Food</p>
				<p class="price">Php 100.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/f1/6e/ea/f16eeafdb6d5eb74742ab91e85e0e968.jpg"> </img>
				<p class="item">Cat Leash</p>
				<p class="price">Php 100.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/76/93/87/769387c07fd6839169d543e66cba8ed4.jpg"> </img>
				<p class="item">Comb</p>
				<p class="price">Php 100.00</p>
			</div>
			
			<div class="box">
				<img class="img" src="https://i.pinimg.com/564x/cb/61/2f/cb612fdec87eea826ff7947bea9a751e.jpg"> </img>
				<p class="item">Dog Shampoo</p>
				<p class="price">Php 100.00</p>
			</div><br>
		<a href="https://drive.google.com/file/d/1cSmQO39y16bFcUVemvcZHUiWG_zWpBKO/view?usp=sharing" class="button">Contact me</a>
	</div>
	</body>







</html>
