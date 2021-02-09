# Projet Spark - Covid-19 VS Societé 2020

## Sujet
Le but du projet est d'exploiter les données sur le covid-19 et les données des sociétés radiées en france. Le but étant de constater si la covid-19 a eu ou non un impacte sur les radiations des entreprises.

## Problématique
__Quel est l'impacte de la covid sur les sociétés en France sur l'année 2020 ?__

## Prérequis
Pour lancer le projet il faut disposer :
- D'un environement anaconda :
    - Python
    - Jupyter notebook

- Spark téléchargé en local sur sa machine

## Installation

Pour pouvoir travailler sur un environement spark avec python, nous allons utiliser pyspark. Pour cela vous devez :

- Créer un nouvel environement conda ou (de préférence) cloner un environement que vous avez déjà avec jupyter notebook
- Télécharger sur son nouvelle environement :
    - Pyspark : `pip install pyspark`
    - Findspark : `pip install findspark`

## Architecture du projet
Dans le projet vous retrouverez :

- Le dossier `src` qui contient le notebook d'analyse du sujet
- Le dossier `data` qui contient les données du projet. Vous retrouverez le fichier zip `donnees_covid_societes.zip` qu'il faut deziper avec le même nom
- Le dossier `result` qui contient les résultats de l'analyse faites sur le sujet.

## Start projet

Pour lancer le projet, activer votre environement avec pyspark de téléchargé. Lancer la commande `jupyter notebook` et dirigez vous vers le fichier `societe_vs_covid` dans le dossier `src` du projet.

Exraire les fichiers de `donnees_covid_societes.zip` qu'il faut deziper dans un dossier avec le même nom.


Vous pouvez alors exécuter le notebook

Enjoy :wink: 

# Résultats obtenus

Le pdf `src/societe_vs_covid.pdf`contient les résultats du notebook
