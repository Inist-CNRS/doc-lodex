# cross-by

La routine `cross-by` croise les éléments pour un champ ou plusieurs champs et compte le nombre d’occurences de chaque croisement. 

Elle crée les paires \(`source` et `target`\) entre les éléments de 2 champs \(champs identiques ou différents\) déclarés selon :

* /api/run/cross-by/**identifiant1/identifiant1/**
* /api/run/cross-by/**identifiant1/identifiant2/**

et compte, pour chaque paire, le nombre de co-occurrences.

Cette routine se comporte comme la routine [pairing-with](pairingwith.md) , le petit `+`:  elle sait interpréter les paramètres associés aux graphiques: 

* Nombre max de champs \(`=maxSize`\)
* Valeur maximum à afficher \(`=maxValue`\)
* Valeur minimum à afficher \(`=minValue`\)
* Trier par valeur/label \(`=sortBy`\) 

Elle peut, en particulier, être utilisée avec les formats [Network](../../administration/modele/format/network.md) \(Réseau\) et [Heat Map](../../administration/modele/format/heatmap.md) \(carte de chaleur\).

**Attention :** dans le cas où cette routine s'applique à un seul champ \(**/api/run/cross-by/identifiant1/identifiant1/\)**, elle conserve les **`auto-paires`** \(`source` et cible identiques **"**`target`**"**\). Cela peut être intéressant avec le format [Heat Map](../../administration/modele/format/heatmap.md) pour visualiser la diagonale, mais peut être gênant avec d'autres formats. 

         **Exemple:** [**https://lodex9310-changclim.dboard.inist.fr/api/run/cross-by/jpw2/jpw2?maxSize=100&minValue=2&orderBy=value/desc**](https://lodex9310-changclim.dboard.inist.fr/api/run/cross-by/jpw2/jpw2?maxSize=100&minValue=2&orderBy=value/desc) 

