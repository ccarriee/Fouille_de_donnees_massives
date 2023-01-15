# Fouille de données massives 

Dans le cadre du Master 2 SISE, nous avons suivi un cours de fouille de données massives dont le but était de nous apprendre à lier le big data et le data mining afin de réaliser des analyses sur des données volumineuses. Pour valider cette matière, nous devions réaliser un projet qui consiste à classifier des données dans un contexte déséquilibré. Les données sont désésquilibrées puisqu'il y a très peu de transactions frauduleuses dans le fichier. 

Concernant les données, elles proviennent d'une grande enseigne de la distribution ainsi que d'organismes bancaires (Banque de France et FNCI). Chaque ligne représente une transaction par chèque dans un magasin de l'enseigne. Le but est de prédire la variable FlagImpaye, qui prend comme valeur 0 si la transaction a été acceptée et 1 si elle a été refusée.

Vous pouvez trouver dans un fichier .ypynb le projet effectué avec le code commenté. Le plan d'analyse du projet est le suivant : 

- Découverte des données en réalisant des statistiques descriptives pour mieux comprendre la situation et les enjeux
- Test de plusieurs modèles de machine learning afin de prédire au mieux la variable cible.
