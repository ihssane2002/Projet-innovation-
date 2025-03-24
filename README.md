# 🛠️ Prédiction des Pannes pour IDSUD Energies

##📌 Description

🚀 Dans le cadre d'un projet d'innovation avec IDSUD Energies, j'ai développé un modèle de maintenance prédictive pour le système hybride Nheolight, qui comprend :

☀️ Panneaux solaires

🌬️ Éoliennes

🔋 Batteries

💡 LEDs

## 🎯 Objectif : Anticiper les pannes des composants afin d'améliorer la fiabilité du système et de réduire les coûts de maintenance.

## 🔧 Technologies Utilisées

🐍 Python

☁️ Google Colab

📊 Bibliothèques ML :

Scikit-learn (Isolation Forest, XGBoost)

Pandas, NumPy, Matplotlib

## 🔍 Modèle de Maintenance Prédictive

Le projet repose sur deux étapes clés :

1️⃣ Détection des anomalies avec Isolation Forest

✅ Analyse des tendances des données issues des panneaux solaires, éoliennes, batteries et LEDs.
✅ Identification des écarts anormaux entre la production attendue et la production réelle.

2️⃣ Prédiction supervisée avec XGBoost

✅ Utilisation des anomalies détectées comme entrées pour un modèle supervisé.
✅ Prédiction de la probabilité de panne dans les 3 jours suivants.

## 📈 Performances des Modèles

Précision Globale pour chaque composant

☀️ Panneaux solaires: 84 %

🌬️ Éoliennes: 96 %

🔋 Batteries: 92 %

💡 LEDs: 91 %

## 🚀 Installation et Utilisation

🔹 1. Cloner le dépôt

git clone https://github.com/ihssane2002/Projet-innovation.git 


🔹2. Exécuter le notebook sur Google Colab

📂 Ouvrir maintenance_predictive.ipynb sur Google Colab.

