# Projet de sélection YouCode : Exploration de Données avec Python 🚀

## 1. Présentation du besoin traité
Dans le cadre de l'intégration d'une fonctionnalité d'Intelligence Artificielle pour les recommandations de l'entreprise **Sell4All** (vente de vêtements d'occasion), ce projet consiste à réaliser une première exploration et préparation des données clients. L'objectif est de nettoyer et d'analyser le jeu de données pour le rendre exploitable par les futurs modèles d'IA.

## 2. Étapes suivies pendant la réalisation
1. **Configuration de l'environnement :** Installation de Miniconda, Jupyter Notebook et des bibliothèques requises (`pandas`, `matplotlib`).
2. **Exploration initiale :** Lecture du fichier CSV, affichage des premières lignes et analyse du résumé technique (types de données et valeurs non nulles).
3. **Analyse Statistique :** Calcul des moyennes et médianes pour l'âge et les dépenses, ainsi que le calcul de la médiane d'âge par pays (Bonus).
4. **Visualisation :** Création d'un graphique à barres avec Matplotlib pour visualiser le total des dépenses par pays.
5. **Nettoyage des données (Data Cleaning) :** 
   - Suppression des clients ayant dépensé moins de 10 €.
   - Suppression des lignes en double.
   - Sélection des colonnes pertinentes (Country, Age, Gender, Customer spendings).
   - Exportation vers un nouveau fichier CSV propre.

## 3. Fonctionnalités développées et éléments finalisés
- Un Jupyter Notebook (`.ipynb`) contenant tout le code Python documenté.
- Des cellules Markdown expliquant en détail le résumé technique des données.
- Un graphique clair et lisible illustrant les dépenses par pays.
- Un jeu de données final, propre et prêt pour l'IA (`dataset-sell4all-cleaned.csv`).

## 4. Difficultés rencontrées et solutions mises en place
- **Difficulté :** La configuration de l'environnement et la gestion des répertoires de travail (s'assurer que Jupyter lisait le bon fichier CSV).
  - **Solution :** Utilisation de la bibliothèque `os` pour vérifier le répertoire de travail courant et lister les fichiers présents (`os.getcwd()` et `os.listdir()`).
- **Difficulté :** Comprendre la différence d'utilisation entre les cellules "Code" et "Markdown" sur Jupyter pour répondre aux questions théoriques.
  - **Solution :** Exploration de l'interface de Jupyter Notebook pour structurer le rendu final avec une séparation claire entre l'exécution logique et la documentation.

## 5. Mode d'exécution du projet (Prérequis)
Pour exécuter ce projet sur votre machine locale, suivez ces étapes :

1. Installez [Miniconda](https://docs.anaconda.com/miniconda/).
2. Ouvrez Anaconda Prompt et installez les dépendances nécessaires avec la commande suivante :
   ```bash
   conda install jupyter pandas matplotlib
