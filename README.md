# Netflix Insights — Analyse de données

Bienvenue dans **Netflix Insights**, un projet d'analyse exploratoire de données basé sur le catalogue Netflix de septembre 2021. Ce projet a été réalisé dans le cadre de l'apprentissage des bases de la data science avec Python et Jupyter Notebook.


## Objectifs du projet

Ce projet a pour but de :
- Découvrir et comprendre la structure des données Netflix.
- Identifier les tendances autour des films et séries (types, genres, durées, pays, etc.).
- Nettoyer, transformer et visualiser les données pour en tirer des insights intéressants.
- Se familiariser avec l'environnement **Jupyter Notebook**, **Pandas** et les librairies de visualisation comme **Seaborn**, **Matplotlib** ou **Plotly**.


## Fichiers du dépôt

- 'Netflix Data Analysis.ipynb' : Notebook contenant toute l’analyse, avec commentaires, visualisations et interprétations.
- `netflix_titles.csv` : Jeu de données source (fourni, disponible  sur Kaggle).
- `README.md` : Ce fichier de documentation du projet.


## Veille technologique : AI Watch
### Intelligence Artificielle (IA)
L’intelligence artificielle désigne l’ensemble des techniques qui permettent à des machines d’imiter une forme d’intelligence humaine. Cela inclut des tâches comme la reconnaissance d’images, le traitement du langage naturel, la prise de décision, ou encore l’apprentissage automatique.

### Machine Learning (Apprentissage automatique)
C’est une sous-branche de l’intelligence artificielle. Le Machine Learning permet à un programme d’apprendre à partir de données, sans être explicitement programmé. L’algorithme détecte des modèles et améliore ses prédictions ou décisions avec le temps.

### Le pré-traitement des données
Avant d’utiliser les données dans un algorithme d’IA ou d’analyse, il faut les nettoyer, transformer et formater. C’est ça le pré-traitement. Par exemple : gérer les valeurs manquantes, convertir les dates, ou transformer des chaînes de caractères en catégories.

### L’analyse descriptive des données
C’est la première étape dans tout projet data, pour explorer et décrire l'information.
Elle permet de comprendre ce que contiennent les données : moyennes, médianes, fréquences, répartitions, graphiques.


### Avant de débuter l’analyse, une veille a été effectuée sur les outils suivants :

- **Jupyter Notebook** : environnement interactif idéal pour l’analyse de données, permet d’écrire du code, des visualisations et des commentaires dans un même document.
- **Pandas** : librairie Python incontournable pour manipuler les données tabulaires.
- **Missingno** : outil pratique pour visualiser les données manquantes.
- **Matplotlib / Seaborn / Plotly** : outils de visualisation permettant de représenter graphiquement les insights.


## Détails des analyses effectuées

### Exploration des données
- Aperçu des premières et dernières lignes
- Informations générales : types de colonnes, nombre de valeurs manquantes, etc.
- Traitement des valeurs manquantes avec `Missingno`
- Nettoyage des variables : `date_added`, `duration`, `listed_in`

### Visualisations
- Répartition des types d’œuvres (Films vs Séries)
- Répartition des pays les plus représentés
- Répartition des œuvres par année de sortie
- Répartition des ratings (TV-MA, PG, etc.)
- Durée des films et des séries
- Genres les plus fréquents
- Top 5 des films et séries les plus longs
- Œuvres par date d’ajout au catalogue
- Réalisateurs les plus prolifiques (et réalisateurs français)

### Observations
- Les films dominent en nombre sur la plateforme.
- Les genres les plus populaires incluent les documentaires, les comédies et les drames internationaux.
- Les années 2018-2020 sont particulièrement riches en ajouts de contenus.
- De nombreux contenus sont internationaux, mettant en lumière la diversité du catalogue Netflix.


## Conclusion

Cette analyse met en évidence l’ampleur et la richesse du catalogue Netflix. Grâce à l’exploration des données, nous avons pu identifier les tendances majeures et mieux comprendre comment Netflix structure son contenu.


## Technologies utilisées

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Missingno


## Auteur

Ce projet a été réalisé dans le cadre d’une initiation à Jupyter Notebook.  

**DINA**   **ALEXANDRE**       **OUDA**

