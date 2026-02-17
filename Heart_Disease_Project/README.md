# Analyse et Prédiction des Maladies Cardiaques par Apprentissage Automatique
## Description du projet
Ce projet vise à **analyser, prédire et visualiser les risques de maladies cardiaques** à l’aide de techniques d’**apprentissage automatique (Machine Learning)**.  
Il couvre l’ensemble du **cycle de vie d’un projet data** : du prétraitement des données jusqu’au déploiement d’une application interactive.

L’objectif principal est de fournir un outil d’aide à la décision permettant d’estimer le risque de maladie cardiaque à partir de données cliniques.
## Objectifs:
- Nettoyer et préparer des données médicales
- Identifier les caractéristiques les plus pertinentes
- Réduire la dimension des données
- Entraîner et comparer plusieurs modèles de Machine Learning
- Évaluer les performances des modèles
- Visualiser les résultats
- Déployer une application interactive accessible à l’utilisateur
## Méthodologie et flux de travail
Le projet suit les étapes suivantes :
1. **Prétraitement des données**
   - Nettoyage des données
   - Gestion des valeurs manquantes
   - Normalisation / standardisation

2. **Sélection des caractéristiques**
   - Analyse de corrélation
   - Importance des variables
   - Réduction du bruit

3. **Réduction de la dimensionnalité**
   - Analyse en Composantes Principales (ACP / PCA)

4. **Apprentissage supervisé (Classification)**
   - Régression Logistique
   - Arbres de Décision
   - Forêts Aléatoires
   - Machines à Vecteurs de Support (SVM)

5. **Apprentissage non supervisé**
   - K-Means
   - Clustering hiérarchique

6. **Évaluation des modèles**
   - Accuracy
   - Précision
   - Rappel
   - F1-score
   - Matrice de confusion

7. **Visualisation**
   - Graphiques statistiques
   - Visualisation des clusters
   - Représentation des composantes principales

8. **Déploiement**
   - Création d’une interface utilisateur avec **Streamlit**
   - Déploiement via **Ngrok**
   - Hébergement du code source sur **GitHub**

## Technologies utilisées
### Langage
- Python
### Librairies principales
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `streamlit`
### Outils
- Git & GitHub
- Ngrok
- Google Colab
## Interface utilisateur
Une application **Streamlit** permet :
- d’entrer les données d’un patient
- d’obtenir une prédiction du risque de maladie cardiaque
- de visualiser les résultats de manière intuitive
L’application est déployée temporairement via **Ngrok**.
