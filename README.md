# Student Performance Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success)](#)

## Présentation du Projet
Ce projet utilise la **Régression Linéaire Simple** pour prédire le score total d'un étudiant en fonction de ses habitudes d'étude. L'objectif est de démontrer l'impact direct de l'investissement personnel sur la réussite académique.

Initialement conçu comme un modèle de régression multiple, l'analyse de corrélation a permis de simplifier le modèle pour se concentrer sur la variable la plus significative : **les heures d'étude hebdomadaires**.

## Analyse des Données (EDA)
L'analyse exploratoire a révélé une forte corrélation entre le temps d'étude et la note finale :
* **Corrélation (Pearson) :** 0.81224
* **Distribution :** La majorité des scores se concentrent entre 70 et 100 points.



## Stack Technique
* **Langage :** Python
* **Librairies :**  `pandas` & `numpy` (Manipulation de données)
    * `matplotlib` & `seaborn` (Visualisation)
    * `scikit-learn` (Machine Learning)

## Résultats du Modèle
Le modèle de régression simple a été entraîné avec un split de 70/30 (Train/Test).

* **Erreur Moyenne Absolue (MAE) :** ~7.16
* **Interprétation :** Le modèle prédit le score final avec une marge d'erreur moyenne de seulement 7 points, ce qui est très performant pour une régression simple.
