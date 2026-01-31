# Méthodes Numériques

* Estimation de quantités de type $\theta := \mathbb{E}[f(X)]$
* Présentation de la méthode de Monte Carlo
* Loi forte des grands nombres
* Modélisation de variables en finance via les semi-martingales d'Itô
* Lien avec les équations aux dérivées partielles (EDP) via la formule de Feynman-Kac


## 1. Mesure de l'erreur de Monte Carlo 

* Théorème central limite.
* Construction d'intervalles de confiance asymptotiques.
* Estimation de la variance (usage des fonctions std en Python et R).
* Théorème de Slutsky.
* Méthode Delta pour les fonctions de moyennes.

## 2. Simulation de variables aléatoires 

* Méthode de l'inverse de la fonction de répartition (fonction quantile).
* Simulation de lois discrètes (Bernoulli) et continues (Exponentielle).
* Approximation pour la loi normale.
* Méthode de Box-Muller pour simuler des variables normales indépendantes.

## 3. Méthodes de réduction de variance 

* 3.1 Variable antithétique : Exploitation de la symétrie de la loi (ex: Loi Uniforme, Normale).
* 3.2 Variable de contrôle : Utilisation d'une variable corrélée dont l'espérance est connue.
* 3.3 Fonction d'importance (échantillonnage préférentiel) : Changement de probabilité pour favoriser les événements rares.
* 3.4 Méthode de stratification : Partitionnement de l'espace d'état en strates.
* Allocation optimale de Neyman.
* Stratification proportionnelle.

## 4. Simulation de processus stochastiques 

* 4.1 Simulation d'un mouvement brownien : Discrétisation temporelle et propriétés.
* 4.2 Simulation d'une équation différentielle stochastique (EDS) : 
* 4.2.1 Simulation exacte de processus d'Itô (ex: Modèle de Vašíček).
* 4.2.2 Schéma d'Euler.
* 4.2.3 Schéma de Milstein.
* 4.3 Application à l'évaluation de produits dérivés : Exemple de l'option asiatique.

## 5. Méthodes des différences finies 

* 5.1 Formule de Feynman-Kac : Lien entre espérance stochastique et solution d'EDP.Principe de comparaison : Unicité de la solution.
* 5.2 Schéma explicite : Discrétisation arrière, maillage et condition de monotonie
* 5.3 Schéma implicite : Résolution d'un système linéaire matriciel.
* 5.4 $\theta$-schéma : Combinaison convexe (ex: Schéma de Crank-Nicholson).

# 6. Méthodes numériques en contrôle stochastique 

* 6.1 Principe de programmation dynamique : Équation de Bellman et théorème de vérification.
* 6.2 Approche par Monte Carlo : Utilisation de maillages et de barycentres.
* 6.3 Exemple - Gestion de portefeuille : Modèle de Heston et utilité exponentielle.
* 6.3.1 Réduction de dimension.
* 6.4 Schéma explicite en contrôle : Application des différences finies au contrôle optimal.

[Plan/Cours de N. Baradel](https://www.nicolasbaradel.fr/enseignement/ressources/cours_methodes_numeriques_finance.pdf)