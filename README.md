# Analyse-Des-Sentiments

#### Travail Pratique

> Machine Learning

Support Vector Machine (SVM)

> Introduction et principe de base

Les SVMs sont une famille d’algorithmes d’apprentissage automatique qui permettent de 
résoudre des problèmes de classification, de régression et de détection d’anomalie. Ils sont connus pour leurs solides garanties théoriques, leur grande flexibilité ainsi que leur simplicité d’utilisation même sans une connaissance de data maning.

(Le data mining couvre l’ensemble des outils et méthodes qui permettent à partir de grandes bases de données. On parle aussi de fouille, forage ou prospection des données, d’extraction de connaissance à partir de données.)

Ils ont été développés dans les années 1990 à partir d’une théorie d’apprentissage statistique développé par les informaticiens russes Vladimir vapnik et Alexey Chervonenkid, leur principe est simple « ils ont pour but de séparer les données en classes » à l’aide d’une frontière, de sorte que la distance entre différents groupes de données et la frontière qui les sépare soit maximale. 

Cette distance est aussi appelée « Marge » cet ainsi qu’ils sont qualifiés de « séparateurs à vaste marge » étant données le plus proches de la frontière

> Types de problèmes visés

Les SVMs sont utilisés dans une variété d’applications (recherche d’informations, vision par ordinateur, bio-informatique) notamment parce qu’à la différence des réseaux de neurones (Inspiré des neurones de cerveau ce sont des fonctions mathématiques qui crée des 
connexions qui apparaissent ou se renforce en fonction de diffèrent stimuli et produisent une action), on peut les utilisés sans comprendre leur fonctionnement : 

il existe des jeux d’hyperparamètre par défaut, pour la classification, la régression ou à détection d’anomalie, C’est l’un de leurs principaux avantages.

Nous citons le kernel ridge régression pour la régression ou le one class SVM pour la détection d’anomalie 

> Quelques exemples 

On s’intéresse à un phénomène f (éventuellement non-déterministe) a partie d’un __entrées__ x, qui produit une __sortie__ y = f(x) 

Le but est de retrouver f à partir de la seule observation d’un certain nombre de couples entrée & sortie {(𝑥𝑖,𝑦𝑖) : i=1, . . ., n}

On considère un couple (X, Y) de variables aléatoires à valeurs dans X*Y. 
Seul le cas ou Y = {-1,1} (classification) on peut étendre au cas |𝑦|=m>2 et au cas y = R

> Example de cas d’apprentissage
 

> Référence

