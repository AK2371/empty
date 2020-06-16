<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width , initial-scale=1">
	<title>Our Menu</title>
	<style>
		*{
			box-sizing: border-box;
			overflow: auto;
		}
		h1{
			margin-bottom: 70px;
			margin-top: 30px;
		}
		.row{
			width: 100%;
		}
		@media (min-width: 992px) {
			.col-lg-3
			{
				float: left;
				border: 1px solid black;
				background-color: grey;
				margin: 5px;
			}
			.col-lg-3{
				width: 32%;
				height: 200px;
			}
		}
		@media (min-width: 768px) and (max-width: 991px){
			.col-md-2
			{
				float: left;
				border: 1px solid black;
				background-color: grey;
				margin: 5px;

			}
				.col-md-2{
					width: 48%;
					height: 200px;
				}
		}
		@media (max-width: 767px){
			.col-xs-1
			{
				float: left;
				border: 1px solid black;
				background-color: grey;
				margin: 5px;
			}
			.col-xs-1{
				width: 98%;
				height: 200px;
			}
		}
		h1{
			text-align: center;
		}
		#p1{
			background-color: #D98880;
			position: sticky;
			top: 0px;
			left: 1000px;
			border: 1px solid black;
		}
		#p3{
			background-color: #C0392B;
			position: sticky;
			top: 0px;
			left: 1000px;
			border: 1px solid black;
		}
		#p5{
			background-color: #F9E79F;
			position: sticky;
			top: 0px;
			left: 3000px;
			border: 1px solid black;
		}
		.comp{
			height: 20px;
		}
		p{
			height: 200px;
			width: 100%;
			margin-left: 10px;
		}

	</style>
</head>
<body>
	<h1>Our Menu</h1>
	<div class="row">
		<div class="col-lg-3 col-md-2 col-xs-1">
			<div>
				<span id="p1">Chicken</span>
			</div>
			<div><p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut eliquip ex ea commodo consequat.</p></div> 
		</div>
		<div class="col-lg-3 col-md-2 col-xs-1">
			<div>
				<span id="p3">Beef</span>
			</div>
			<div><p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut eliquip ex ea commodo consequat.</p></div>
		</div>
		<div class="col-lg-3 col-md-2 col-xs-1">
			<div class="comp">
				<span id="p5">Sushi</span>
			</div>
			<div><p>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut eliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint accaecat cupidatat non proident, sunt in cupia qui officia deserunt mollit anim id laborum.</p></div>
		</div>
	</div>
</body>
</html>
