<html>
	<head>
		<title>A rainy evening
		</title>
		<script src="jquery.js"></script>
		<script>
		
			$(document).ready(function(){
					$(".div2").hide();
 				$(".div1").click(function()
 					{
    					$(".div1").slideUp(2000).slideDown(2000).css("color", "black").hide(10000);




 			 		}
 			 	);
 			 	$(".div1").click(function(){
  				$(".div2").show(30000).scss("color", "green").css("color", "black");
					});


			});

		</script>
		<style>
			p {
  			color: red;
  			text-align: center;
			} 
			.div1 {
				width: 5000px;
				height: 500px;
				background-color: red;
				border-color: black;
				border-radius: 20%;
				text-align: center;
				display: table-cell;
				vertical-align: middle;
				margin-left: 600px;
				position: relative;
				font-size: 50px;


			}
			.div2 {
				width: 5000px;
				height: 500px;
				background-color: green;
				border-color: black;
				border-radius: 20%;
				text-align: center;
				display: table-cell;
				vertical-align: middle;
				margin-left: 600px;
				position: relative;
				font-size: 50px;


			}
		</style>
	
		

		

	</head>
	<body>
		
		<div class="div1">God Bye Hamid Khan <br>Dubai will miss you;(
			
		</div>
		<div class="div2">  Welcome to Pakistan!!<br> Sweet Home
			
		</div>
		

	</body>
</html>
