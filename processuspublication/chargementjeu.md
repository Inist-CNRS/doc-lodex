# Chargement du jeu de données

Après vous être authentifié, le système propose cet écran : 

![](../.gitbook/assets/image%20%2834%29.png)

Cliquer sur le bouton "Commencez en chargeant un corpus de données". L'écran suivant s'affiche :

![](../.gitbook/assets/image%20%2816%29.png)

Deux actions sont à effectuer successivement :

* “Choix du parser à appliquer” ; il s'agit du loader permettant de convertir le format du fichier de données à charger vers le format importable dans Lodex
* "Choix du fichier à charger", pour sélectionner ce fichier de données, extraites de Istex ou d'une autre  source.

## 1 - Choix du loader

Cliquer sur le texte correspondant. La liste des loaders disponibles s'affiche. 

![](../.gitbook/assets/image%20%2817%29.png)

 Choisir le loader qui correspond à votre format source :

  
- tableau CSV avec précision sur le séparateur : point-virgule, tabulation, tabulation et guillemets, virgule, automatique,  
- fichier au format json, soit extrait de l'API ISTEX, soit déjà compatible avec LODEX \(export de LODEX\), soit "avec un tableau" pour, d'autres sources, notamment complexes,  
- fichier XML utilisant le vocabulaire TEI ou MODS ou ATOM ou RSS ou SKOS,  
- fichier zip extrait avec l'outil [dl](https://dl.istex.fr/)  :  "`résultat brut de dl.istex.fr`" importe un certain nombre de champs avec intitulés anglais ; "`résultats de dl.istex.fr`" importe des champs plus nombreux avec intitulés français, et des données mieux structurées pour certains graphiques \(catégories hiérachiques notammment\).



## 2 - Choix du fichier à charger

Pour cette étape, vous allez récupérez votre fichier, de format conforme au loader choisi, soit sur votre disque dur, soit à partir d'un site distant. Dans ce dernier cas, il vous est demandé de préciser l'URL du site distant sur lequel votre fichier est hébergé.

Le système vous propose cet écran : 

![](../.gitbook/assets/image%20%2819%29.png)

 Cliquez sur le bouton `IMPORTER UN FICHIER` ou  `IMPORTER DEPUIS UNE URL`



Si votre fichier se trouve sur votre disque dur, cliquez sur le bouton `IMPORTER UN FICHIER`. 

Le système ouvre l'explorateur de fichiers de l'ordinateur ; naviguer pour sélectionner le fichier à charger, puis cliquez sur le bouton `Ouvrir`.

 **Remarque** : Le fichier à charger ne doit contenir que des caractères conformes à UTF8 ; s'il s'agit d'un tableau CSV, la colonne A et la ligne 1 ne doivent pas être vides ; les entêtes de colonnes ne doivent pas comporter de caractères spéciaux \(par exemple les caractères de ponctuation\).

Quand le fichier est importé, le système vous propose cet écran \(extrait\) :

![](../.gitbook/assets/image%20%2824%29.png)

Que lire sur cet écran ?

![](../.gitbook/assets/image%20%2821%29.png)

l'affichage en haut à droite "ERREUR" est normal à ce stade. Il disparaitra après l'étape suivante,  [création de l'URI](creationuri.md).

Les trois actions permises à l'aide du **bouton** `+` **:**  ![Les boutons d&apos;ajout de colonne](../.gitbook/assets/ecranchargementdonnees6.png) 

