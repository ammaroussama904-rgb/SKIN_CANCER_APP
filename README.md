# Système Intelligent de Diagnostic des Lésions Cutanées (Skin Cancer Detection)

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/Framework-Flask-lightgrey.svg)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/DL-TensorFlow%20/%20Keras-orange.svg)](https://www.tensorflow.org/)

##  Présentation du Projet
Ce projet consiste en une plateforme d'aide au diagnostic dermatologique basée sur l'intelligence artificielle. L'application permet d'analyser des images de lésions cutanées pour classifier les tumeurs en deux catégories : **Bénignes** ou **Malignes**.

L'objectif est de fournir un outil de dépistage rapide, s'appuyant sur des réseaux de neurones convolutifs (CNN) de pointe, pour assister les professionnels de santé ou sensibiliser les utilisateurs.

 ### Architecture Technique

 Deep Learning & Computer Vision
* Modèle :** Architecture **VGG16** (Transfer Learning).
* Optimisation :** Fine-tuning des dernières couches denses pour la classification binaire.
* Prétraitement :** Normalisation des pixels, redimensionnement (224x224) et Data Augmentation pour améliorer la robustesse du modèle.
* Gestion des modèles :** Intégration via **Git LFS** pour le stockage des poids lourds (`.h5`).

### Backend & Infrastructure
* **Framework :** Flask (Python) pour la logique métier et l'API de prédiction.
* **Base de données :** MySQL pour la persistance des données patients et l'historique des diagnostics.
* **Sécurité :** Gestion des sessions et hachage des mots de passe.

##  Installation et Déploiement

### Prérequis
* Python 3.9+
* Serveur MySQL

### Configuration locale
1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/ammaroussama904-rgb/SKIN_CANCER_APP.git](https://github.com/ammaroussama904-rgb/SKIN_CANCER_APP.git)
   cd SKIN_CANCER_APP
