# Projet Spark - Covid-19 VS Societé 2020

## Sujet
Le but du projet est d'exploiter les données sur le covid-19 et les données des société radié en france. Le but etant de constater si le covid-19 à eu ou non un impacte sur les radiations des entreprises.

## Problematique
__Quelle est l'impacte du covid sur les société en France sur l'année 2020 ?__

## Prérequis
Pour lancer le projet il faut disposer :
- D'un environement anaconda :
    - Python
    - Jupyter notebook

- Spark télécharger en local sur ca machine

## Installation

Pour pouvoir travailler sur un environement spark avec python, nous allons utiliser pyspark. Pour cela vous devez :

- Créer un nouvelle environement conda ou (de preference) cloner un environement que vous avez deja avec jupyter notebook
- Télécharger sur son nouvelle environement :
    - Pyspark : `pip install pyspark`
    - Findspark : `pip install findspark`

## Architecture du projet
Dans le projet vous retrouverez :

- Le dossier `src` qui contient le notebook d'analyse du sujet
- Le dossier `data` qui contient les données du projet. Vous retrouverez le fichier zip `donnees_covid_societes.zip` qu'il faut dezipé avec le meme nom
- Le dossier `result` qui contient les resultats de l'analyse faites sur le sujet.

## Start projet

Pour lancer le projet, activer votre environement avec pyspark de telecharger. Lancer la commande `jupyter notebook` et dirigez vous vers le fichier `societe_vs_covid` dans le dossier `src` du projet.

Exraire les fichiers de `donnees_covid_societes.zip` qu'il faut dezipé dans un dossier avec le meme nom.

Vous pouvez alors executer le notebook

Enjoy :wink: 
