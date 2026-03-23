
# 🐧 Penguin Analysis — EDA, PCA, UMAP, Clustering & ML Models

Analyse complète et reproductible du dataset **Palmer Penguins**, réalisée dans un cadre professionnel de data science.  
Le projet couvre l’ensemble du pipeline analytique : EDA, feature engineering, réduction de dimension, clustering, modèles supervisés et interprétabilité.

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
