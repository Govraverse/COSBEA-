# COSBEA-
Une éducation de qualité pour un avenir meilleur
📁 Organisation du projet

Crée un dossier appelé :

site_ecole

Puis mets dedans :

index.html
etablissement.html
classe.html
cours.html
activites.html
style.css
ecole.jpg

Renomme la photo que tu as envoyée en ecole.jpg.

1️⃣ Page d’accueil index.html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Collège Bilingue Etoile des Anges</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>COLLÈGE BILINGUE ETOILE DES ANGES</h1>

<h3>Douala PK19</h3>

<p><b>Devise :</b> Discipline - Travail - Succès</p>

<img src="ecole.jpg" width="600">

<p>Bienvenue sur le site officiel de la classe <b>Seconde C1</b>.</p>

<h2>Menu</h2>

<ul>
<li><a href="etablissement.html">Présentation de l'établissement</a></li>
<li><a href="classe.html">Présentation de la classe</a></li>
<li><a href="cours.html">Cours et enseignants</a></li>
<li><a href="activites.html">Activités scolaires</a></li>
</ul>

<h2>Inscription</h2>

<form>

Nom : <input type="text"><br><br>

Prénom : <input type="text"><br><br>

Email : <input type="email"><br><br>

<input type="submit" value="S'inscrire">

</form>

</body>
</html>
2️⃣ Page établissement etablissement.html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Présentation de l'établissement</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Présentation de l'établissement</h1>

<img src="ecole.jpg" width="600">

<p>
Le Collège Bilingue Etoile des Anges situé à Douala PK19 offre
une éducation de qualité pour un avenir meilleur.
</p>

<h2>Devise</h2>

<p>Discipline - Travail - Succès</p>

<a href="index.html">Retour à l'accueil</a>

</body>
</html>
3️⃣ Page classe classe.html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Présentation de la classe</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Classe : Seconde C1</h1>

<h2>Responsables</h2>

<ul>
<li>Professeur titulaire : M. NGEMEN NGOK Gavin</li>
<li>Chef de classe : MBEY Daniel G.</li>
<li>Chef adjoint : TCHEPGANG Divax C.</li>
<li>Nombre d'élèves : 35</li>
</ul>

<h2>Emploi du temps</h2>

<table border="1">

<tr>
<th>Jour</th>
<th>Matières</th>
</tr>

<tr>
<td>Lundi</td>
<td>Mathématiques, Chimie, Histoire, Français</td>
</tr>

<tr>
<td>Mardi</td>
<td>Mathématiques, Physique, Géographie, Anglais</td>
</tr>

<tr>
<td>Mercredi</td>
<td>SVT, Chimie</td>
</tr>

<tr>
<td>Jeudi</td>
<td>Français, EPS, Permanence, TM</td>
</tr>

<tr>
<td>Vendredi</td>
<td>Physique, Anglais, Informatique, ECM</td>
</tr>

</table>

<br>

<a href="index.html">Retour à l'accueil</a>

</body>
</html>
4️⃣ Page cours cours.html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Cours et enseignants</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Cours et enseignants</h1>

<table border="1">

<tr>
<th>Matière</th>
<th>Enseignant</th>
</tr>

<tr><td>Mathématiques</td><td>M. NGUEMEN Gavin</td></tr>
<tr><td>Physique</td><td>M. TAGNE Alexandre</td></tr>
<tr><td>SVTEEHB</td><td>Mme TSAKENG N.</td></tr>
<tr><td>Informatique</td><td>M. NDEGNI Eugène</td></tr>
<tr><td>Français</td><td>M. BISSA Loïc</td></tr>
<tr><td>Anglais</td><td>Mme NGUEA BELL</td></tr>
<tr><td>Histoire</td><td>M. MISSECK Alex</td></tr>
<tr><td>Géographie</td><td>M. POUMVE Perez</td></tr>
<tr><td>ECM</td><td>Mme NGOUNTSOP Doriance</td></tr>
<tr><td>Chimie</td><td>M. AGOFACK Paul</td></tr>
<tr><td>EPS</td><td>Mme KANA Yvonne</td></tr>

</table>

<br>

<a href="index.html">Retour à l'accueil</a>

</body>
</html>
5️⃣ Page activités activites.html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Activités scolaires</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Activités de la classe</h1>

<ul>

<li>Journée Culturelle</li>
<li>Gastronomie</li>
<li>Club Informatique</li>
<li>Compétitions Sportives</li>
<li>Sorties scolaires</li>

</ul>

<a href="index.html">Retour à l'accueil</a>

</body>
</html>
🎨 Bonus (pour que ton site soit beau) style.css
body{
font-family: Arial;
background-color: #f0f0f0;
text-align: center;
}

h1{
color: darkblue;
}

table{
margin: auto;
background-color: white;
}

ul{
list-style: none;
}

a{
color: red;
text-decoration: none;
}
