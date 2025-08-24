# EDA-Titanic

Objectif

Explorer le dataset Titanic (Kaggle).

Comprendre les facteurs qui influencent la survie.

Produire des visualisations claires et une petite interprétation.


Plan du projet


1\_Introduction

Présentation rapide du Titanic dataset.
Objectif : identifier les variables les plus corrélées à la survie.


2\_Chargement et aperçu des données

pandas.read\_csv()
df.head(), df.info(), df.describe().


3\_Nettoyage des données

Gestion des valeurs manquantes (Age, Cabin, etc.).
Transformation de variables catégorielles (Sex, Embarked).

4\_Analyse exploratoire

Répartition des survivants vs non survivants.
Analyse par sexe, âge, classe (Pclass), famille, etc.
Visualisations avec Seaborn (heatmap des corrélations, barplots, histograms).

5\_Insights




# 🚢 Analyse exploratoire du Titanic (Kaggle)

## 🎯 Objectif
Ce projet explore le célèbre dataset du Titanic afin d’identifier les facteurs ayant influencé la survie des passagers.  
L’objectif est de mettre en pratique une **analyse exploratoire de données (EDA)** avec Python et d’en tirer des insights clairs, illustrés par des visualisations.

---

## 📊 Étapes principales

### 1. Répartition des survivants
- Taux de survie global : ~38%.
- Forte mortalité globale (62%).

### 2. Analyse par sexe
- Femmes : ~74% de survie.  
- Hommes : ~19% de survie.  
➡️ Le sexe est un facteur majeur de survie.

### 3. Analyse par classe (Pclass)
- 1ère classe : plus de chances de survie.  
- 3ème classe : très faible taux de survie.  
➡️ La classe sociale influençait directement la survie.

### 4. Analyse par âge
- Les enfants avaient globalement plus de chances de survie.  
- La majorité des victimes étaient des adultes.

### 5. Analyse par taille de la famille
- Familles petites (2 à 4 personnes) : meilleure survie.  
- Passagers seuls ou grandes familles : survie plus faible.

### 6. Heatmap des corrélations
- Variables les plus corrélées à la survie : **Sexe, Classe, Âge**.  
- D’autres variables (comme `Fare`) montrent aussi un effet.

---

## 🛠️ Outils utilisés
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Jupyter Notebook  

---

## 📂 Structure du projet

