# Prédiction des Accidents d'Assurance Habitation

Ce projet utilise des algorithmes de machine learning pour prédire les accidents d'assurance habitation en fonction des données fournies. Il s'appuie sur deux fichiers principaux de données : **train_Insurance.csv** et **test_Insurance.csv**.

## Description des Fichiers

- **train_Insurance.csv**  
  Ce fichier contient les données d'entraînement utilisées pour entraîner les modèles de machine learning. Il comprend 5012 observations décrites par 12 attributs et une variable cible `claim`, indiquant si un accident a été signalé.

- **test_Insurance.csv**  
  Ce fichier est utilisé pour tester les performances des modèles prédictifs après l'entraînement. Il contient des données similaires au fichier d'entraînement, mais sans la variable cible `claim`.

## Objectif

L'objectif principal de ce projet est de prédire si un accident sera signalé (`claim = 1`) ou non (`claim = 0`) en fonction des données d'entrée.

## Contenu du Projet

- **Data Exploration et Prétraitement** : 
  - Analyse des données.
  - Nettoyage des données (traitement des valeurs manquantes, encodage des variables catégoriques, normalisation des valeurs, etc.).

- **Modélisation** :
  - Entraînement de différents modèles de machine learning (ex. : régression logistique, arbres de décision, forêts aléatoires, etc.).
  - Validation croisée pour évaluer les performances des modèles.

- **Évaluation** :
  - Calcul des métriques de performance telles que la précision, le rappel, le F1-score et l'AUC-ROC.

## Comment Exécuter le Projet

1. **Pré-requis** :
   - Python 3.8 ou plus récent.
   - Les bibliothèques suivantes doivent être installées :
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```

2. **Étapes** :
   - Clonez ce dépôt :  
     ```bash
     git clone https://github.com/votre-utilisateur/nom-du-projet.git
     cd nom-du-projet
     ```
   - Placez les fichiers **train_Insurance.csv** et **test_Insurance.csv** dans le répertoire du projet.
   - Exécutez le notebook principal pour entraîner et évaluer les modèles :  
     ```bash
     jupyter notebook projet.ipynb
     ```

## Presentation
https://docs.google.com/presentation/d/1b8i1FlI-h4Kv-PpKJc4hurK2IjKtZMUd/edit?usp=drive_link&ouid=111568998039075228445&rtpof=true&sd=true

