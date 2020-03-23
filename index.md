# Analyse dynamique des mouvements de foule
https://github.com/ARE2020-G10G11/MVT_FOULES/blob/master/blog.md
Déterminer le temps nécessaire pour le retour au calme d'une foule (si possible) en modélisant chaque individu dans un espace 2D

## English version

Determine the amount of time necessary for a panicked crowd to go back to normal by representing each individual in a 2D space
## Présentation de l'équipe

|(´・ω・｀)| ( ͡° ͜ʖ ͡°) | ಠ_ಠ | ᕕ( ᐛ )ᕗ |
|-----|--|--|--|
| Z. ADJISSA | 	S. PERMALNAICK |	R. AICHI |	X. WEI |






## Description synthétique du projet: Les humains modélisés sont représentés dans un espace 2D par deux états:
L’état paniqué (1) et l’état calme (0).
Chaque individu est caractérisé par son « taux de crédulité » entre 0 et 1 cette valeur représentera la susceptibilité
D’un individu à être convaincu par la réalité de la menace.
Chaque individu possède un « taux de persuasion» entre 0 et 1 cette valeur représentera la capacité de l’individu
À convaincre ses voisins directs.
Un voisinage est le nombre d’individus plus proches voisins, il sera déterminé par les modélisateurs.
Un individu sera persuadé si la moyenne TDP des individus différents de son voisinage est supérieure à son TDC.
Les TDC et TDP sont répartis aléatoirement tout en gardant une moyenne de 0,5 pour chacun.
Le ou les initiateurs de la panique seront fabriqués par les modélisateurs (TDP, TDC) et position
Les individus suivent le membre de leur voisinage au TDP le plus élevé.

**Problématique :** Une foule en délire peut-elle revenir à l’ordre d’elle-même ?

**Hypothèse principale :**-Une foule en délire ne peut pas se calmer d’elle-même.

**Hypothèses secondaires :** -Un seul individu ne peut pas, de lui-même déclencher un mouvement de foule.
-La position du ou des initiateurs est primordiale à la bonne propagation de la panique.

**Objectifs :**- Evaluer l’instant t (s’il existe) à partir duquel toutes les cellules sont retournées dans leur état initial.
- Evaluer l’effet moyen d’une cellule sur ses voisins et voir si certaines sont démesurément influentes.


**Critère(s) d'évaluation :**-Nombre de cellules initialement excitées pour une propagation
Totale de la panique.




## Présentation structurée des résultats

Présentation du choix de modélisation, des outils, du code et des résultats (tableaux, courbes, animations...) (**avec une analyse critique**).

## Lien vers page de blog : <a href="blog.html"> C'est ici ! </a>

## Bibliographie :

**Carte mentale de vos mots-clés, en utilisant** <a href="https://ibb.co/jGwH0nJ">Framindmap </a> 

Liste de l'ensemble des ressources bibliographiques utilisées pour vos travaux. **<= Indiquez le canal utilisé pour les trouver (Google Scholar, sources wikipedia, ressources en ligne SU, ...)**
