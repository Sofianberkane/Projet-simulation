# Simulation des Modèles Dynamiques d'une Machine à Laver

Ce projet implémente une simulation des dynamiques d'une machine à laver en utilisant des modèles mathématiques basés sur la méthode numérique d’Euler semi-implicite. L'objectif est de modéliser les phases critiques du cycle de lavage, telles que le lavage, le rinçage et l'essorage, en tenant compte des paramètres physiques.

## Contenu du Projet

- **Phase de Rotation Rapide** : Implémentation des équations et simulations associées à la phase d'essorage, où des vitesses élevées induisent des forces centrifuges.
- **Analyse des Forces Dynamiques** : Étude des forces et oscillations induites par le déséquilibre des charges.
- **Simulation des Interactions** : Simulation de divers paramètres physiques comme le coefficient de frottement, la masse des vêtements, et la géométrie de la machine.

## Fichiers Principaux

- **`projet-simulation-sofian-berkane.ipynb`** : Notebook contenant le code source pour les simulations, les visualisations et les analyses.
- **Données et Graphiques** : Génération de graphiques pour étudier le comportement des systèmes dynamiques.

## Technologies Utilisées

- **Python** : Langage principal pour l'analyse et les calculs.
- **Bibliothèques Utilisées** :
  - `numpy` : Calcul numérique.
  - `matplotlib` : Visualisation des résultats.
  - Toute autre bibliothèque nécessaire est mentionnée dans le code.

## Instructions pour l'Exécution

1. Installez Python 3.x et les dépendances nécessaires avec `pip install -r requirements.txt`.
2. Lancez le notebook Jupyter avec la commande :
   ```bash
   jupyter notebook projet-simulation-sofian-berkane.ipynb
