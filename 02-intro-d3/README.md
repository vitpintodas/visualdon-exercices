# Introduction à D3

## Installation
* Allez dans le dossier de l'exercice ```cd 02-intro-d3```
* Installez les packages nécessaires et qui sont dans le package.json ```npm install```
* Démarrez le serveur ```npm start```

:rocket: Vous devriez avoir accès à votre serveur local sur [localhost:8080](http:localhost:8000) :rocket:

Le fichier html se trouve dans ```public/index.html``` et l'exercice se déroulera dans le fichier ```src/ìndex.js```, où vous allez écrire vos premières lignes de code en d3!

**Important**: dans cet exercice seulement les méthodes de d3 pourront être utilisées. 

## Manipuler les DOM
Créez 3 cercles de 40px de rayon et placez-les respectivement à : (50,50), (150,150), (250,250)


## Attributs
* Changez la couleur du deuxième cercle
* Déplacez de 50px vers la droite le premier et le deuxième cercle 

## Append
Rajoutez du texte en dessous de chaque cercle

## Événements
Alignez verticalement les cercles en cliquant sur le dernier cercle

## Données 
Vous avez à disposition les données suivantes: ```[20, 5, 25, 8, 15]```

Ces données représentent la hauteur des rectangles que vous allez dessiner avec la méthode ```data(data).enter()``` que nous avons vue en cours. Les rectangles auront une largeur fixe de 20px et doivent être alignés en bas l'un à côté de l'autre (comme un graphique en batons ! :bar_chart: )
