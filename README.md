<!DOCTYPE html>
<html>
<head>
	<title>Cristiano Ronaldo</title>
	<style>
		body {
			margin: 0;
			padding: 0;
			overflow: hidden;
			display: flex;
			align-items: center;
			justify-content: center;
			height: 100vh;
		}

		.container {
			display: flex;
			flex-wrap: wrap;
			align-items: center;
			justify-content: center;
			width: 100%;
			height: 100%;
		}

		.item {
			flex: 1 1 25%;
			margin: 20px;
			border-radius: 10%;
			overflow: hidden;
			position: relative;
		}

		.item img {
			width: 100%;
			height: 100%;
			object-fit: cover;
		}

		.item .text {
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			font-size: 2em;
			font-weight: bold;
			color: #fff;
			text-shadow: 2px 2px 2px #000;
			text-align: center;
			z-index: 1;
		}
	</style>
</head>
<body>
	<div class="container">
		<div class="item">
			<img src="https://media.gettyimages.com/id/1454029167/es/foto/cristiano-ronaldo-smiles-as-he-is-unveiled-as-an-al-nassr-player-at-mrsool-park-stadium-on.jpg?s=612x612&w=0&k=20&c=9zmDQV6ZEeYocE-3oCZ-V6aPNPzy2jM5w-SJsO2miOg=" alt="Cristiano Ronaldo">
			<div class="text">The GOAT</div>
		</div>
		<div class="item">
			<img src="https://media.gettyimages.com/id/1245965880/es/foto/al-nassrs-new-forward-cristiano-ronaldo-greets-the-fans-during-his-unveiling-at-the-mrsool.jpg?s=612x612&w=0&k=20&c=hV46l61pz2Lbp-FxxoJOCZa9VCMsRQyCitLsnkksZf4=" alt="Cristiano Ronaldo">
			<div class="text">The Phenomenon</div>
		</div>
		<div class="item">
			<img src="https://media.gettyimages.com/id/1458529419/es/foto/cristiano-ronaldo-of-al-nassr-leads-the-team-out-prior-to-the-saudi-pro-league-match-between.jpg?s=612x612&w=0&k=20&c=5tHseu1TldFB8WRY-bLbSW4j9G21CVB3JEAK36gJvBA=" alt="Cristiano Ronaldo">
			<div class="text">The Legend</div>
		</div>
		<div class="item">
			<img src="https://media.gettyimages.com/id/1245970744/es/foto/portuguese-superstar-ronaldo-wears-jersey-of-al-nassr-before-an-introductory-ceremony-at.jpg?s=612x612&w=0&k=20&c=1g2RsXBN7EKsGBI4STHeXQTot62mEZ5r4NOudh7QmIY=" alt="Cristiano Ronaldo">
			<div class="text">The Master</div>
		</div>
	</div>
</body>
</html>
