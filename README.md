# My second site
<link rel="stylesheet" href="index.html" type="text/index" />
<!DOCTYPE HTML>
<html>
	<head>
		<meta charset = "UTF-8">
		<link rel="stylesheet" href="style1.css" type="text/css" />
		<title>My site</title>
		
		
		
	<script type="text/javascript">
		function RedBg() {document.bgColor = 'red';}
		function WhiteBg() {document.bgColor = 'white';}
		function BlackBg() {document.bgColor = 'black';}
		function GreenBg() {document.bgColor = 'green';}
		function GreyBg() {document.bgColor = 'grey';}
		function BlueBg() {document.bgColor = 'blue';}
		
		function RedText() {document.write("<style='color:red'>test string</div>");}

		function BlueText() {document.write(str.fontcolor( "blue" )); alert(str.fontcolor( "blue" )); }
	</script>
	
	</head>
	<body>
	<ul class = "Bg"> Bg color:
		<li><input type="button" id="but_1" value="White" onClick="return WhiteBg()"></li>
		<li><input type="button" id="but_1" name="but_1" value="Blue" onClick="return BlueBg()"></li>
		<li><input type="button" id="but_1" name="but_1" value="Grey" onClick="return GreyBg()"></li>
		<li><input type="button" id="but_1" name="but_1" value="Black" onClick="return BlackBg()"></li>
		<li><input type="button" id="but_1" name="but_1" value="Red" onClick="return RedBg()"></li>
		<li><input type="button" id="but_1" name="but_1" value="Green" onClick="return GreenBg()"></li>
	</ul>
	
	</body>
