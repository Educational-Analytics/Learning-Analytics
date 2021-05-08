# Example de Dashboard interactif
## Description courte du scenario d’analyse

Dans le cadre de cette analyse on cherche à développer au maximum les ressources des plateformes d’enseignement comme Moodle afin de proposer aux 3 grands acteurs d’un établissement : administrateurs, enseignants et apprenants, une meilleure vision des indicateurs de performance au sein des cours impartis.

## Cas d’utilisation

De nombreux Dashboard sont créés afin d’aider les élèves et les enseignants à avoir une idée générale de la performance d’une classe. Avec l’hybridation des cours, on peut approfondir les analyses de données disponibles et ainsi développer de nouveaux indicateurs permettant une meilleure interprétation des résultats de classe pour un cours donné.

### Orientés enseignants

Dans le cas concernant l’enseignant, il cherche à connaitre de plus près comment chaque apprenant réalise les activités de son cours et à quel pourcentage elles ont été réalisées. Ceci lui permet d’avoir non seulement une vue personnalisée mais aussi une vue générale des comportements de classe au fur et à mesure que les activités du cours sont réalisées.

### Orientés apprenants

Pour ce qui concerne les apprenants la vision est différente. Contrairement aux enseignants, eux ils cherchent à connaitre sa performance par rapport au reste de la classe (moyenne de classe – moyenne élève), à savoir facilement quelles activités il a déjà réalisées et lesquelles doivent être rendues dans les jours à venir.

## Inputs

### Logdata



|Prénom |  Nom  | ID (int)|
|-------|------|---------|
|Arthur | Vidal  | 5|
|Camille | Blanc| 6|
|Evan| Lemaitre | 8|
|Adrien| Lip | 23|
|Anais | Lefevre | 9|

  
### Pourcentage moyen de réalisation de l'activité par cours

Dans ce tableau on trouve différents cours avec ces différentes activités. Les activités ne sont pas réalisées à 100% par tous les élèves, un pourcentage de réalisation est mesuré pour chaque activité. Ici on a pris une moyenne des pourcentages de réalisation des activités de tous les élèves pour chaque activités des 4 learnings.

Learnings | Activité 1 | Activité 2 | Activité 3 | 
|---------|------------|------------|------------|
Learning 1 | 0.7 | 0.8 | 0.8 |
Learning 2 | 0.5 | 0.4 | 0.3 |
Learning 3 | 0.6 | 0.5 | 0.6 |
Learning 4 | 0.2 | 0.3 | 0.4 |

### Notes des apprenants par activité pour un cours précis

Prénom | Nom | Activité 1 | Activité 2 | Activité 3 | Activité 4 | Moyenne de notes des activités|
|------|-----|------------|------------|------------|------------|-------------------------------|
Arthur | Vidal | 17 |	8 |	17 | 15 |	14.25|
Camille	| Blanc |	14 | 18 | 3 |	13 | 12 |
Evan | Lemaitre | 20 | 9 | 16 |	14 | 14.75 |
Adrien | Lip | 10 | 14 | 20 | 16 | 15 |
Anais | Lefevre | 10 | 8 | 13 | 9 | 10 |
Clemence |Garnier | 13 | 6 | 13 | 10 | 10.5|
Leo	| Dumas |	17	| 5 |	13	 | 12	 | 11.75 |
Matteo | Orsat	| 20 |	19 |	20 |	17 |	19 |
Maxime | Laporte	| 2 |	8 |	17 |	17 | 11|



## Indicateur recommandé

Indicateur: Pourcentage de réalisation de l'activité

## Exemples

### Objectif enseignants

Pour un cours de mathématique on a 4 activités différentes qui ont été données aux apprenants. Un Dashboard permettant de connaitre la performance de la classe est fait afin de proposer une visualisation simple, claire mais pertinente à l’enseignant.
Premièrement, il dispose d’une liste de tous les élèves du cours donné. A droite on trouve la moyenne du cours pour chaque élève mais aussi leur rang en fonction de leur moyenne.

![Dashboard Professeur](https://github.com/Hype-13/Learning-Analytics/blob/main/Dashboard%20Examples/Exemples/Exemple%20Dashboard%20Professeur.PNG)

Le graphe en dessous permet à l’apprenant de connaitre les notes par élevé et par activité. La séquence se trouvant au-dessus pour chaque activité correspond à la meilleure note et la couleur à un élève. Ainsi, l’enseignant fait connaissance de la performance par élève au cours des activités. Si un élève se trouve toujours dans la même position séquentielle pour toutes les activités alors le professeur pourra conclure que son engagement est constant. Tandis que si la position de l’élève en fonction des activités varie de manière importante il pourra observer un désengagement et envisager de l’aide supplémentaire nécessaire pour l’apprenant concerné.

![Dashboard Interactif Professeur](https://github.com/Hype-13/Learning-Analytics/blob/main/Dashboard%20Examples/Exemples/Exemple%20Dashboard%20Interactif%20Professeur.PNG)

### Objectif apprenants

D’autre part, la création d’un Dashboard aide aussi l’apprenant à avoir une idée générale de sa performance personnelle mais aussi en fonction de la classe. Ici il trouvera son rang de classe, le pourcentage de réalisation des activités, l’activité réalisée et celles à venir.

![Dashboard Eleve](https://github.com/Hype-13/Learning-Analytics/blob/main/Dashboard%20Examples/Exemples/Exemple%20Dashboard%20Eleve.png)

## Bibliographie
