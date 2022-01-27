[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrienarcuri/notebooks-dm)

# Cours DM

Liste des ressource pour le cours de DataMining

## CMs

- [CM2 - Analyse descriptive](CMs/notebooks/CM2_Analyse_descriptive.ipynb)

### Installation de l'environnement de travail

# Installation

## Installation avec Anaconda (recommandé)

Anaconda est une distribution de Python spécialement dédiée au calcul scientifique. Elle inclut par défaut un grand nombre de librairies permettant d'effectuer des calculs massifs rapidement (les chemins de codes critiques étant implémentés en C/Fortran et non en Python).

Pour l'installer, suivre les informations sur le site officiel : https://www.anaconda.com/

La distribution est gratuite, open source et disponible sur la plupart des environnements. Toujours préférer la version 64 bits si compatible avec le système.

Les TD sont basés sur la version 3.7 de Python.

### Installer les librairies supplémentaires

Anaconda contient déjà de nombreuses librairies en son sein, mais des librairies supplémentaires sont requises pour pouvoir suivre les TD en entier.

Pour les installer, ouvrir une invite de commande Anaconda (menu démarrer -> Anaconda -> "Anaconda Prompt") et exécuter la commande suivante : 

conda install -y -c conda-forge -c plotly pandas==0.25.3 numpy==1.17.4 jupyter notebook plotly==4.4.1 matplotlib==3.1.2 plotly-orca requests psutil pandas-profiling scikit-learn==0.22.1 numba==0.42.0 umap-learn fbprophet hdbscan

### Ouvrir les notebooks Jupyter

Un notebook Jupyter est une représentation interactive sous forme de page Web de l'interpréteur Python. On peut le voir comme une évolution visuelle de taille d'un interpréteur sous forme "lignes de commandes" classique.

Tous les TD sont sous formes de notebook. Pour ouvrir des notebooks, les instructions ci-dessous seront à reproduire à chaque fois :

* Menu démarrer -> Anaconda -> Jupyter Notebook
* (Si applicable) choisir le navigateur à utiliser pour ouvrir les notebooks
* Naviguer vers le dossier où vous avez extrait les zip des TD
* Cliquer sur un notebook pour l'ouvrir dans une nouvelle page

Pour terminer une session, fermez les pages et la fenêtre du terminal.

## Alternative dans le Cloud : Google Colab

Vous pouvez également lancer le notebook sur Google Colab : https://colab.research.google.com
Le Notebook s'exécutera dans le Cloud de Google (jusqu'à atteinte d'un quota maximum d'exécution).

Pour télécharger des fichiers sources dans Google Colab, merci de lire ce lien : https://medium.com/@simonprdhm/2-mani%C3%A8res-simple-de-charger-un-fichier-csv-dans-google-colab-3b86616d248a 

Pour se familiariser avec Colab: https://colab.research.google.com/notebooks/welcome.ipynb?hl=fr

## Autres alternatives

- Une autre plateforme de Notebook en ligne (créé par JetBrains): https://datalore.jetbrains.com
- Un IDE pour scientifique - Spyder (intégré à Anaconda) : https://www.spyder-ide.org
- Un IDE pour codeur - gratuit comme ou VS Code: https://code.visualstudio.com
- Un IDE commercial Pycharm Pro (la version gratuite ne prend pas en charge les Notebooks): https://www.jetbrains.com/fr-fr/pycharm/