# Partie Learning Analytics 
***
Dans cette partie du projet, nous allons étudier les différents impacts des ressources sur la scolarité des étudiants suivants des cours hybridés ou non. 

La comparaison du nombre d'inscrit aux cours en ligne au fil des années peut aussi être intérssante pour voir si les cours en lignes attirent les étudiants ou non. Cela permett aussi de voir si les campus ont mis de plus en plus de cours en ligne ou non. 

Nous allons aussi étudier les différentes relations qui existent entre les étudiants via les forums sous les ressources qui sont un moyens de disucssion entre les campus. 
De plus, sous les ressources, il est possible de communiquer via des messages si l'étudiant à des questions. L'étude du type de messages envoyé, c'est à dire un message entre deux étudiants, ou bien entre un étudiant et un professeur ou bien entre deux professeurs, permettra de voir quel cours est le plus actif tout comme quel professeur l'est aussi. 

# Echantillonage au sein d'une séquence pédagogique 

## Description courte du scénario d'analyse

Le but de cet échantillonnage est de comparer les notes et les absences des étudiants en fonction du pourcentage de suivis des cours dans les modules en ligne. En effet, dans les cours cent pourcent hybridés, un étudiant à la possibilité de sauter des vidéos ou quizz d'entraînement s’il le souhaite. Dans ce cas, il est intéressant de voir l'évolution des notes pour voir si suivre un cours partiellement est suffisant pour tel ou tel étudiant ainsi que de voir si le cours du professeur est trop riche et non essentiel. Les abscences des étudiants reflètent aussi leur comportement vis à vis des suivis des cours.  

D'une part, les inscriptions des étudiants au cours en ligne permettent aussi de comparer les différents campus appartenant au groupe Hype13. En effet, cela va permettre de mettre l'accent sur les campus qui ont mis un place un programme en ligne ou non. 

D'autre part, les messages échangés sous les ressources pour apporter de l'aide aux étudiants permettent aussi de voir quelles relations existent entre étudiants/professeurs, étudiants/étudiants et professeurs/professeurs. Cela va aussi permettre de mettre l'accent sur les modules les plus actifs ou non. Les différents membres des campus ont la posisbilité d'échanger aussi via ces messages, nous pourrons donc voir quels campus échangent le plus et dans quels domaines. 

## Tags

Echantillonnage

## Cas d’utilisation

### Orientés concepteurs

Pour un concepteur de vidéo de cours en ligne, le fait que certain étudiant ne suive pas toutes les vidéos ou quizz lui permettra de faire un tri sur les ressources non suivis par la plus part des étudiants.

### Orientés enseignants

Les enseignants, quant à eux auront la possibilité de suivre la proggresion de leurs étudiants et sanctionner ceux qui ne suivent que tèrs partiellement voir pas du tout les modules en ligne.

### Orientés apprenants

Les enseignants, quant à euxn auront la possibilité de suivre la proggresion de leurs étudiants et sanctionner ceux qui ne suivent que tèrs partiellement voir pas du tout les modules en ligne.


### Orientés chercheurs

On peut donc catégeoriser les étudiants suivant leur mode de suivi des cours : ceux qui suivent totalement le module en faisant toutes les ressources à la suite, ceux qui suivent une bonne partie mais pas complètement, ceux qui complètent les ressources partiellement, ceux qui suivent très peu les différentes étapes de la partie ressource et enfin ceux qui sautent énormément de ressources voir qu'ils n'en suivent pas du tout. Les absences réflètent aussi ce non-suivi des cours et permettent d'appuyer l'explication de la chute des notes des étudiants. Un étudiant ayant beaucoup d'absences verra son niveau baissé. 

Quant aux inscriptions au sein d'un campus qui a mis en place l'hybridation des cours, il sera intéréssant de comparer ce nombre suivant les années. 

Enfin, pour la partie des messages, il est intérssant de voir quelles sont les relations possibles entre étudiants et professeurs et quels campus échangent le plus. 

## Inputs

Etude des notes/absences en fonction des pourcentges de suivi 

|User id |  Absences  | Notes| Pourcentage de suivi |
|-------|------|---------|-------|
|21 | 29  | 11| 20-40|
|22 | 21| 13|40-60 |
|23| 22 | 12|40-60 |
|24| 21 | 15|40-60 |
|25 | 18 | 16|60-80 |

Etude des inscriptions en fonction des campus et des années

|Campus|  Année d'inscrpition  | 
|-------|------|
|Sorbonne | 2017  | 
|Sorbonne | 2019| 
|SciencePo| 2018 | 
|SciencePo| 2015 | 
|SciencePo | 2016 | 

Etude des types de messages échangés en fonction des modules 

|Course id|  Module  | Type de message échangé |
|-------|------|-----|
|11 | DeepLearning  | étudiantvsprof
|12 | Sociologie| étudiantvsétudiant
|13| TheorieInformation | profvsprof
|14| ModeleSequence | étudiantvsprof
|15 | TextMining | étudiantvsétudiant


## Outputs

|Pourcentage de suivi |  Moyenne des absences  | Moyenne des notes|
|-------|------|---------|
|0-20 | 49.333333  | 5.777778|
|20-40 | 35.259259| 10.851852|
|40-60| 22.814815 | 13.333333|
|60-80| 13.074074 | 15.333333|
|80-100 | 3.148148 | 19.000000|


|Année d'inscription |  Campus  | Nombre d'inscription|
|-------|------|---------|
|2015 | CYTech  | 2|
|2015 | EcolePolytechnique| 3|
|2015| ESSEC | 1|
|2015| HEC | 3|
|2015 | SciencePo | 3|

|Type de message |  Module  | Nombre de messages|
|-------|------|---------|
|étudiantvsétudiant | DeepLearning  | 5|
|étudiantvsétudiant | ModeleSequence| 10|
|étudiantvsétudiant| Sociologie | 9|
|étudiantvsétudiant| TextMining | 6|
|étudiantvsétudiant | TheorieInformation | 5|


## Exemple 

Comme on peut le constater dans le graph suivant, la moyenne des notes des étudiants chute considérablement lorsque ceux ci ne suivent pas correctement les différentes ressources dans un module. De plus, un étudiant très fréquement absent voit aussi ses notes chutés, ce qui est logique. 

![Alt text](https://github.com/Hype-13/Learning-Analytics/blob/main/Exemple/Image/A.PNG)

Dans l'étude du nombre d'inscriptions en fonction des campus, on remarque directement qu'en 2017 le campus CYTech compte un nombre très élevé d'incriptions aux cours en ligne. En contraste, l'Université de Lille enregristre le moins d'inscriptions durant l'année 2017.  

![Alt text](https://github.com/Hype-13/Learning-Analytics/blob/main/Exemple/Image/B.PNG)

Dans cette partie, nous allons nous concentrer sur l'étude des différents messages échangés à l'aide des databases que nous avons créé plus haut. On constate en premier lieu que dans l'intéraction étudiant/professeur, le module Deep Learning est en tête. Le professeur de cette matière est très actif au contraire des professeurs de Modèle Sequence et de Théorie de l'Information. 

![Alt text](https://github.com/Hype-13/Learning-Analytics/blob/main/Exemple/Image/C.PNG)

L'utilisation des réseaux sociaux permet de visualier les relations entre les étudiants à travers les messages échangés. En effet, les étudiants de différents campus peuvent communiquer et intéragir dans le forum d'un module commun. Dans les prochains schémas, on peut constater quels campus intéragissent le plus entre eux. 

![Alt text](https://github.com/Hype-13/Learning-Analytics/blob/main/Exemple/Image/D.PNG)

Ici, on se concentre sur un seul étudiant pour voir avec qui il a des relations. Lorsque l'on regarde les intéractions de Max qui vient de HEC, on peut voir qu'il a échangé avec un autre étudiant de son campus mais aussi avec deux étudiants de l'Université de Lille et un autre venant de l'Ecole Polytechnique. 

![Alt text](https://github.com/Hype-13/Learning-Analytics/blob/main/Exemple/Image/E.PNG)

## Bibliographie 

## Légitimisation de l'analyse
