[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrienarcuri/notebooks-dm)

# Cours de Data Mining - ISIAD MIAGE Toulouse - UT1 Capitole  - 2022

Liste des ressources pour le cours de DataMining

## CMs

- [CM1 - Introduction et premiers concepts](https://docs.google.com/presentation/d/e/2PACX-1vRNtygfleTbJolFaH-9--SL_-075bvIwDX8q77OejHs9-DPxLkKOKjWVRC9UvITKgrOfUUoDTffRNq7/pub?start=false&loop=false&delayms=60000)
- [CM1 (bis) - Rappels Statistiques](https://docs.google.com/presentation/d/e/2PACX-1vRr2BMr6BaTapsdxQmo74Fd2M84fFYfPTlWYmKcLK1zfDAkRtsTXGY7R4waKDh8ofHNZwT3Bw7SDRjU/pub?start=false&loop=false&delayms=60000)
- [CM2 - Déroulement d’une étude de Data Mining](https://docs.google.com/presentation/d/e/2PACX-1vTgE1wlx2IPnAxQD-7RBgoc7i3DmWVpvtFAa9OE0V87aZJHpxluaFk9jUJ9hnzIOKRh4WqMDZk5WPTr/pub?start=false&loop=false&delayms=60000)
- [CM2 - Notebook - Analyse descriptive](CMs/notebooks/CM2_Analyse_descriptive.ipynb)
- [CM3- Déroulement d’une étude de Data Mining (Suite) + Clustering](https://docs.google.com/presentation/d/e/2PACX-1vT90vnH6VyY6_rUo03uQbqH49R2LfVAq7GRw4LqQsuNeHUNIRzjr97RIlqaZu4adKaW5VC57zQYcR-z/pub?start=false&loop=false&delayms=60000)
- [CM4 - Modèles DM + Modélisation prévisionnelle d’une série temporelle](https://docs.google.com/presentation/d/e/2PACX-1vTjTVxXwNl4Z_3nZ7GO9mAT5c8UeE89XzQN_wwSESbJk8MJI3eavyxT7JYHdvkvW8J574HUbrxI6GPA/pub?start=false&loop=false&delayms=60000)

 
 ## TDs
 
 - [TD1](./TDs/TD1)
 - [TD2](./TDs/TD2)
 - [TD3](./TDs/TD3)
 - [TD4](./TDs/TD4)

 ## Projet Collectif

 Voir [les consignes du Projet Collectif](./Projet%20Collectif).

--- 

## Installation de l'environnement de travail pour les TDs

### Installation avec Anaconda (recommandé)

Installer la distribution Anaconda sur votre ordinateur: https://www.anaconda.com/products/individual

### Installer les librairies supplémentaires

Anaconda contient déjà de nombreuses librairies en son sein, mais des librairies supplémentaires sont requises pour pouvoir suivre les TD en entier.

#### Sur Windows

<img src="https://docs.anaconda.com/_images/win-anaconda-prompt2.png" alt="drawing" width="250"/>

Pour les installer, ouvrir une invite de commande Anaconda (menu démarrer -> Anaconda -> "Anaconda Prompt") et exécuter la commande suivante : 

```bash
conda install -y -c conda-forge -c plotly pandas==0.25.3 numpy==1.17.4 jupyter notebook plotly==4.4.1 matplotlib==3.1.2 plotly-orca requests psutil pandas-profiling scikit-learn==0.22.1 numba==0.42.0 umap-learn fbprophet hdbscan
```

#### Sur Linux / MacOS

Ouvrir un terminal et tapez:

```bash
conda install -y -c conda-forge -c plotly pandas==0.25.3 numpy==1.17.4 jupyter notebook plotly==4.4.1 matplotlib==3.1.2 plotly-orca requests psutil pandas-profiling scikit-learn==0.22.1 numba==0.42.0 umap-learn fbprophet hdbscan
```

### Ouvrir les notebooks Jupyter

Un notebook Jupyter est une représentation interactive sous forme de page Web de l'interpréteur Python. On peut le voir comme une évolution visuelle de taille d'un interpréteur sous forme "lignes de commandes" classique.

Tous les TD sont sous formes de notebook. Pour ouvrir des notebooks, les instructions ci-dessous seront à reproduire à chaque fois :

* Menu démarrer -> Anaconda -> Jupyter Notebook
* (Si applicable) choisir le navigateur à utiliser pour ouvrir les notebooks
* Naviguer vers le dossier où vous avez extrait les zip des TD
* Cliquer sur un notebook pour l'ouvrir dans une nouvelle page

Pour terminer une session, fermez les pages et la fenêtre du terminal.

### Alternative dans le Cloud : Google Colab

Vous pouvez également lancer le notebook sur Google Colab : https://colab.research.google.com
Le Notebook s'exécutera dans le Cloud de Google (jusqu'à atteinte d'un quota maximum d'exécution).

Vous pouvez aussi directement appuyer sur le bouton suivant : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adrienarcuri/notebooks-dm)

> ⚠️ Pensez toujours à charger un fichier le fichier CSV correspondant lorsqu'il y a la ligne suivante : `pd.read_csv("fichier.csv")` et adapter le chemin vers le fichier. Lisez la suite pour en savoir comment faire.

Pour télécharger des fichiers sources dans Google Colab, merci de lire ce lien : https://medium.com/@simonprdhm/2-mani%C3%A8res-simple-de-charger-un-fichier-csv-dans-google-colab-3b86616d248a 

Pour se familiariser avec Colab: https://colab.research.google.com/notebooks/welcome.ipynb?hl=fr

### Autres alternatives

- Une autre plateforme de Notebook en ligne (créé par JetBrains): https://datalore.jetbrains.com
- Un IDE pour scientifique - Spyder (intégré à Anaconda) : https://www.spyder-ide.org
- Un IDE pour codeur - gratuit comme ou VS Code: https://code.visualstudio.com
- Un IDE commercial Pycharm Pro (la version gratuite ne prend pas en charge les Notebooks): https://www.jetbrains.com/fr-fr/pycharm/

## Remerciements

Sincère remerciement à :
- [Thomas CATTELLE](thomas@cattelle.net) pour m'avoir communiqué ses supports de cours (revue pour l'occasion) et de TDs
- [Michael PENARANDA](https://fr.linkedin.com/in/michael-penaranda-a85b50180) et [Trimane](https://trimane.fr) qui m'ont permis de reprendre ce cours en partenariat avec l'UTC Capitole de Toulouse.
- a l'[équipe de pédogique du master MIAGE / ISIAD de l'UTC Capitole](https://www.ut-capitole.fr/formations/nos-diplomes/masters/master-2eme-annee-mention-miage-parcours-type-ingenierie-des-sytemes-d-information-pour-l-aide-a-la-decision-isiad-322437.kjsp)
- aux élèves sans qui il n'y aurait pas de cours !

