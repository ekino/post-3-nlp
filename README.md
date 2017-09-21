# Notebook Jupyter accompagnant les posts de blog "Handson de quelques tâches courantes en NLP" et "Simple NLP tasks tutorial"


## Introduction

Ce notebook regroupe les exemples présents dans le post "Handson de quelques tâches courantes en NLP" (et sa version anglaise "Simple NLP tasks tutorial"). Ce sont des exemples simples de tâches courantes en NLP implémentées en Python en utilisant les librairies SpaCy et NLTK.
Dans ce repository sont donc présents un notebook jupyter exécutées (*Exemples de tâches simples de NLP avec SpaCy et NLTK-run.ipynb*), le même notebook mais non exécuté (*Exemples de tâches simples de NLP avec SpaCy et NLTK.ipynb*) et un fichier *requirements.txt* pour l'installation des différents packages nécessaires.

## Environnement

Il est conseillé d’utiliser un environnement Anaconda en Python 3.5 :

```
$ conda create --name spacy_nltk_examples python=3.5
$ source activate spacy_nltk_examples
```

Il est ensuite nécessaire d'installer les packages présents dans le fichier *requirements.txt* :

```$ pip install -r requirements.txt```

Enfin pour ouvrir le notebook, il faut se placer dans le répertoire le contenant et lancer le serveur notebook via la commande :

```$ jupyter notebook```

Le notebook s’ouvre alors dans le navigateur et on accède au tableau de bord. Il faut ensuite sélectionner le fichier en *.ipynb* puis le faire tourner cellule par cellule (Menu Cell puis Run Cells) ou toutes les cellules d'un coup (Menu Cell puis Run All).
