# box
<!DOCTYPE html>
<html>
<head>
	<title>Sample Website</title>
	<!-- Just copy the script tag and paste in before the </head> of your website-->
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
</head>
<body>
<h1> This is my sample website.</h1>
</body>
</html>
