# Calcul Stochastique

1. Random Walk
2. Brownian Motion
3. Martingales
4. Quadratic Variation
5. Itô’s Lemma
6. The Itô Integral
7. GBM Solution
8. Girsanov Theorem
9. Feynman-Kac



# Modélisation et Calcul Stochastique

## I. Processus en temps discret et espace d'état fini
**1. Le modèle binomial à une période**
* 1.1 Modélisation : Processus aléatoire et information.
* 1.2 Couverture d'option : Notion de martingale et mesure risque-neutre.

**2. Le modèle binomial à $T$ périodes**
* 2.1 Modélisation et mesure martingale.
* 2.2 Couverture d'options européennes.
* 2.3 Couverture d'options américaines.
* 2.4 Prise en compte des dividendes.

**3. Éléments de correction des exercices.**

---

## II. Calcul stochastique en temps continu
**1. Mouvement Brownien et modèle de Black-Scholes**

**2. Intégrale stochastique par rapport au mouvement brownien**
* 2.1 Processus simples.
* 2.2 Processus admissibles.

**3. Processus d'Itô, variation quadratique et lemme d'Itô**
* 3.1 Définitions et résultats généraux.
* 3.2 Application : Dynamique du prix, processus de portefeuille et couverture en Delta ($\Delta$) dans le modèle de Black-Scholes.

**4. Théorème de Girsanov**
* 4.1 Changement de mesure.
* 4.2 Application : Mesure risque-neutre $\mathbb{Q}$ dans le modèle de Black-Scholes.

**5. Théorème de représentation et couverture d'options quelconques**

**6. Extensions multivariées**
* 6.1 Processus multivariés.
* 6.2 Versions multivariées des théorèmes principaux.
* 6.3 Application au modèle de Black-Scholes en dimension $n=2$.
* 6.4 Application à un modèle à taux d'intérêt stochastique.

**7. Contrôle optimal stochastique**
* 7.1 Un problème issu de la gestion de portefeuille.
* 7.2 Approche par dualité.
* 7.3 Approche par équation de **Hamilton-Jacobi-Bellman (HJB)**.

**8. Éléments de correction des exercices.**

**9. Compléments sur l'espérance conditionnelle $\mathbb{E}[X|\mathcal{F}_t]$.**

---

## Formules Clés
* **Dynamique de Black-Scholes :**
$$dS_t = \mu S_t dt + \sigma S_t dW_t$$

* **Lemme d'Itô :**
$$df(t, X_t) = \left( \frac{\partial f}{\partial t} + \mu_t \frac{\partial f}{\partial x} + \frac{1}{2} \sigma_t^2 \frac{\partial^2 f}{\partial x^2} \right) dt + \sigma_t \frac{\partial f}{\partial x} dW_t$$

* **Dérivée de Radon-Nikodym (Girsanov) :**
$$\left. \frac{d\mathbb{Q}}{d\mathbb{P}} \right|_{\mathcal{F}_T} = \exp \left( -\int_0^T \theta_s dW_s - \frac{1}{2} \int_0^T \theta_s^2 ds \right)$$

(Plan/Cours de B. Bouchard)