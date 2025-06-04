# Projet Big Data - Université de Montpellier (2024-2025)

Ce projet a été réalisé dans le cadre du Diplôme Universitaire Big Data et Data Science à l’Université de Montpellier. Il s’articule en deux grandes parties :
1. **Traitement de données et économétrie**
2. **Machine Learning appliqué à la sinistralité automobile**

---

## 🔹 1. Traitement de données et économétrie

📁 Dossier : `traitement_econometrie/`

### 🎯 Objectifs
- Nettoyage, enrichissement et croisement de données assurantielles, climatiques et géographiques
- Analyse statistique et économétrique de la sinistralité
- Segmentation climatique du territoire français
- Modélisation de la probabilité et du montant des sinistres

### 📄 Contenu
- `notebook_traitement_econometrie.ipynb` : Notebook Jupyter incluant :
  - Préparation des jeux de données (polices, sinistres, météo, géographie)
  - Analyses descriptives et multivariées (ACP, ACM)
  - Régression logistique sur la sinistralité
  - Clustering sur les assurés non sinistrés
- `rapport_econometrie.pdf` : Rapport complet synthétisant la méthodologie, les résultats et les recommandations

---

## 🔹 2. Machine Learning appliqué à la sinistralité

📁 Dossier : `machine_learning/`

### 🎯 Objectifs
- Identifier les profils de véhicules et d’assurés à risque
- Analyser l'effet du climat sur la sinistralité
- Construire des modèles prédictifs performants (classification & régression)

### 📄 Contenu
- `notebook_ml.ipynb` : Notebook Jupyter contenant :
  - Construction d’un véhiculier de risque
  - Modélisation avec :
    - Régression logistique
    - GLM
    - Arbre de décision
    - XGBoost (classification binaire)
  - Évaluation des performances (précision, rappel, F1-score)
- `rapport_ml.pdf` : Rapport détaillé sur la démarche machine learning et les résultats

---

## 🧰 Outils et technologies

- **Langage** : Python
- **Librairies** : pandas, matplotlib, seaborn, scikit-learn, XGBoost, statsmodels
- **Outils** : Jupyter Notebook
- **Méthodes** : Régression logistique, ACP, clustering hiérarchique (CAH), arbre de décision, GLM, XGBoost

---

## 👤 Auteur

**Clément Amégadjaka**  
Université de Montpellier  
DU Big Data et Data Science 2024–2025
