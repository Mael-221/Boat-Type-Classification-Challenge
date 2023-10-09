# Boat Type Classification Challenge

## Description
Ce notebook illustre ma participation à une compétition de deep learning visant à classer différents types de bateaux. En utilisant un réseau neuronal convolutionnel inspiré du modèle VGG16, j'ai réussi à décrocher la 2ème place parmi les participants de quatre spécialités différentes.

## Caractéristiques du modèle
- **Architecture :** Réseau neuronal convolutionnel avec plusieurs couches Conv2D, MaxPooling2D, BatchNormalization et Dropout.

- **Librairies utilisées :** Tensorflow, Keras, Numpy, Pandas, Seaborn, Matplotlib, Scikit-learn

## Données
Les données utilisées pour cette compétition sont stockées dans le dossier `dataset` et comprennent des images de différents types de bateaux.

## Comment visualiser le notebook
1. Clonez ce repo : `git clone [URL_DU_REPO]`
2. Assurez-vous d'avoir Jupyter Notebook installé. Si ce n'est pas le cas, installez-le avec : `pip install jupyter`
3. Naviguez vers le dossier du repo et lancez Jupyter Notebook : `jupyter notebook`
4. Ouvrez le notebook depuis l'interface de Jupyter pour le visualiser et l'exécuter.

## Installation des dépendances
Pour installer toutes les dépendances nécessaires pour exécuter ce notebook, utilisez le fichier `requirements.txt` fourni.


## Résultats
Le modèle a été entraîné et validé sur les données, avec des graphiques montrant la perte et la précision à la fois pour l'entraînement et la validation. De plus, une matrice de confusion a été générée pour visualiser les performances du modèle sur l'ensemble de validation.
