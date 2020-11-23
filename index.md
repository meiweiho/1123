
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<style type="text/css">
		p{
			color:red;
			margin:5px	;
			cursor:pointer	;
		}
		p:hover{
			background: yellow	;
		}
		.dog{
			position:fixed;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			z-index: 10;
			background: rgba(0,0,0,0.5);
			display: flex;
			justify-content: center;
			align-items: center;
		}
	</style>
</head>
<body>
	<p>撒摩耶犬超可愛</p>
	<h1>阿囉哈</h1>
	<div class="dog">
		<img src="3.jpg">
		</div>
	<script type="text/javascript"> 
		$('p').click(function(){
			$('.dog').slideToggle();
});
			$('img').click(function(){
			$('.dog').slideToggle();
		});
	</script>
</body>
</html>
