
<p align="center">
  <img src="https://raw.githubusercontent.com/allisonhorst/palmerpenguins/master/man/figures/lter_penguins.png" width="60%">
</p>

<h1 align="center">🐧 Penguin Analysis — EDA, PCA, UMAP, Clustering & ML Models</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas">
  <img src="https://img.shields.io/badge/Scikit--learn-ML-green?logo=scikitlearn">
  <img src="https://img.shields.io/badge/XGBoost-Modeling-red?logo=xgboost">
  <img src="https://img.shields.io/badge/CatBoost-Gradient%20Boosting-lightgrey?logo=catboost">
</p>

---

## 📑 Table des matières
- [Objectifs du projet](#-objectifs-du-projet)
- [Structure du dépôt](#-structure-du-dépôt)
- [Analyse exploratoire (EDA)](#-1-analyse-exploratoire-eda)
- [Feature Engineering](#-2-feature-engineering)
- [Réduction de dimension](#-3-réduction-de-dimension)
- [Clustering](#-4-clustering-non-supervisé)
- [Modèles supervisés](#-5-modèles-supervisés)
- [Interprétabilité — SHAP](#-6-interprétabilité--shap)
- [Rapport final](#-rapport-final)
- [Reproductibilité](#-reproductibilité)
- [Auteur](#-auteur)

---

## 📌 Objectifs du projet
- Explorer les caractéristiques morphologiques des trois espèces de manchots.
- Identifier des patterns structurels via ACP (PCA) et UMAP.
- Réaliser un clustering non supervisé (K-means).
- Construire des modèles supervisés pour prédire l’espèce.
- Interpréter les modèles via **SHAP**.
- Produire un rapport final clair et exploitable.

---

## 📂 Structure du dépôt

---

## 🔍 1. Analyse exploratoire (EDA)
- Visualisation des distributions
- Analyse des corrélations
- Détection des outliers
- Comparaison inter-espèces
- Analyse par île et par sexe

---

## 🧩 2. Feature Engineering
- Nettoyage des valeurs manquantes  
- Standardisation  
- Encodage des variables catégorielles  
- Création de nouvelles features pertinentes  

---

## 📉 3. Réduction de dimension
### **PCA**
- Explication de la variance
- Visualisation 2D des clusters naturels

### **UMAP**
- Projection non linéaire
- Séparation plus nette des espèces

---

## 🎯 4. Clustering non supervisé
- K-means avec sélection du nombre optimal de clusters
- Visualisation des clusters dans l’espace PCA/UMAP
- Analyse des profils de clusters

---

## 🤖 5. Modèles supervisés
Modèles testés :
- GradientBoosting  
- XGBoost  
- CatBoost  

Évaluation :
- Accuracy  
- Matrice de confusion  
- Importance des features  

---

## 🧠 6. Interprétabilité — SHAP
- SHAP values globales  
- SHAP values locales  
- Analyse fine des décisions du modèle  

---

## 📄 Rapport final
Le rapport complet (format ODT) est disponible dans le dossier `report/`.  
Il présente :
- la méthodologie  
- les résultats  
- les visualisations  
- les conclusions  

---

## 🚀 Reproductibilité
1. Cloner le dépôt  
2. Installer les dépendances  
3. Exécuter le notebook `Manchot.ipynb`  

---

## ✨ Auteur
Projet réalisé par **Mlooi** dans le cadre d’un travail analytique complet.


