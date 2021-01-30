# box
<!DOCTYPE html>
<html>
<head>
	<title>Sample Website</title>
	<!-- Just copy the script tag and paste in before the </head> of your website-->
	
	
	
	/*여기서 부터복사*/
	<script type="text/javascript">
		document.onkeydown = function (event) {
		     event = (event || window.event);
		     if (event.keyCode == 123 || event.keyCode == 18)
		     {
		           return false;
		     }
		}
		document.addEventListener('contextmenu', event => event.preventDefault());
	</script>
	/*여기까지 복사*/
	
</head>
<body>
<h1> This is my sample website.</h1>
</body>
</html>
