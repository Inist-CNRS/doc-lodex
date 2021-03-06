# exporter le modèle prêt

![mod&#xE8;le d&apos;export](../../../.gitbook/assets/image%20%287%29.png)

Lorsque que vous sélectionnez cette option, le système exporte **uniquement votre paramétrage de base** \(informations générales, sémantisation, affichage, …\) et plus particulièrement les étiquettes \(libellés\) de vos colonnes.  
****

 Ce modèle prêt ainsi exporté est utile si vous souhaitez : 

* réutiliser les données reformatées par LODEX \(voir schéma : constitution du jeu de données A'\)
* mettre à jour les données tout en **conservant les URI générés**, les **nouveaux labels** ainsi que les **résultats des transformers** \(définis lors du 1er import\). \(voir schéma : constitution du jeu de données A''\)

Après export de votre jeu de données \(.csv, .tsv...\), les labels \(étiquettes\) de vos colonnes sont différents de ceux définis dans votre tableau initial \(brut\).

_**Schéma :**_

![](../../../.gitbook/assets/schema-synthetique-modele-pret.png)

> _**Exemple :**_ 
>
> Lors d’un 1er chargement vous aviez une colonne `title_id`  transformée en `titre` et vous aviez concaténé les valeurs de plusieurs colonnes en une seule \(transformeur [FORMAT](../transformers/format.md)\) en définissant un séparateur.
>
> → vous avez besoin de réimporter le fichier .csv produit par LODEX contenant la colonne `titre`, ainsi que la colonne contenant les valeurs concaténées. Vous le rechargez dans LODEX à la place du .csv brut qui ne contient plus les mêmes labels de colonne ni les mêmes valeurs dans les colonnes. 
>
>  **Vous utiliserez le modèle prêt car il sera adapté au .csv exporté.**

