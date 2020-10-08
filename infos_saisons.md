## Premiers pas en HTML et CSS

**Description du projet :**
<br>
HTML et CSS ont été les premiers langages informatiques avec lesquels j'ai travaillé. Ci-dessous, les premières pages web que j'ai eu l'occasion de coder.
<br>

### 1. Le visuel

Nous avons 4 pages web, une pour chaque saison de l'année. Chaque page est composée d'une image et d'un poème sur un fond dégradé en lien avec la saison. En bas de la page, se situent deux liens pour aller soit à la saison précédente, soit à la saison suivante.
<br><br>
L'image utilisée pour le fond est libre de droit.
<br>
J'ai fourni les images utilisées pour chaque saison ainsi que les poèmes.
<br>

<a href="images/saisons/printemps.png"><img src="images/saisons/printemps.png"/></a>
<a href="images/saisons/ete.png"><img src="images/saisons/ete.png"/></a>
<a href="images/saisons/automne.png"><img src="images/saisons/automne.png"/></a>
<a href="images/saisons/hiver.png"><img src="images/saisons/hiver.png"/></a>

### 2. Le code

Pour cette première approche, j'ai codé l'ensemble des pages manuellement afin de mieux intégrer les différentes balises mais aussi les bases en HTML et CSS. 

```javascript
<html>
	<head>
		<title>Printemps</title>
		<meta charset="UTF-8"/>
		<link href="saisons.css" rel="stylesheet" type="text/css"/>
	</head>
	<body class="printemps">
		<div class="content">
			<h1>Printemps</h1>
			
			<div class="img">
				<img src="IMAGES/printemps.jpg" alt="printemps"/>
			</div>
			
			<div class="poème">
				<h2>Aube</h2>
				<p><strong>P</strong>rémices d'une nouvelle lueur d'espoir et</p>
				<p><strong>R</strong>enaissance après la nuit la plus froide.</p>
				<p><strong>I</strong>mprégnant le monde d'une diversité de couleurs</p>
				<p><strong>N</strong>aquît dans les des tréfonds de l'hiver;</p>
				<p><strong>T</strong>raversant la fin couche de neige</p>
				<p><strong>E</strong>t s'élevant vers un ciel bleu,</p>
				<p><strong>M</strong>ultitudes de fleurs tapissent</p>
				<p><strong>P</strong>rairies et vallées de leurs vives couleurs</p>
				<p><strong>S</strong>avourant ainsi le doux soleil de printemps</p>
				<p class="auteur">Audrey Deck</p>
			</div>
			
			<table>
				<tr>
					<td><a href="hiver.html"><img src="IMAGES/gauche.png"/>HIVER</a></td>
					<td><a href="ete.html">ETE<img src="IMAGES/droite.png"/></a></td>
				<tr>
			</table>
		</div>
	</body>
</html>
```

<p align="center">
<a href="audreydeck.github.io">Retour</a>
</p>
