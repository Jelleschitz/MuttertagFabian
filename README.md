<!DOCTYPE html>
<html>
	<head>
		<title>Muttertag</title>
	</head>
	<body>
		<h1 id="myheading">Alles Gute zum</h1>
		<p>
			<img id="myImage"
				 src="./Geschenk.png"
				 alt="Italian Trulli"
				 onclick="
					var image = document.getElementById('myImage');
					image.src = (image.src.endsWith('Geschenk.png')) ? './Kuchen.png' : './Geschenk.png';
				 ">
		</p>
		<h1 id="mysecheading">
			Muttertag 
		</h1>
	</body>
</html>
