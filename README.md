# P5.js
tekening van een huis

<!DOCTYPE html>
<html>
<head>
<meta charset=”utf−8”>
<title></title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.14/p5.js"></script>
<script src="tekening.js"></script>
</head>
<body>
</body>
</html>

var xHouse = 125;
var yHouse = 250;
var xSize = 500;
var ySize = 500;
  
function setup() {
	createCanvas(xSize, ySize);
	background(0, 153, 255);
}

function draw() {
	strokeWeight(2)
	fill(255, 0, 115);
	rect(xHouse, yHouse, 250, 250);
	triangle(125, 250, 375,250, 250, 125);
	fill (153, 255, 51);
	rect(175, 400, 50, 100);
	rect(175, 300, 50, 50)
	rect(275, 300, 50, 50)
	rect(275, 400, 50, 50)
	
