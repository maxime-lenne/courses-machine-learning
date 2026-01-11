![Diabete](img/diabete.jpeg)

Ce projet propose une démonstration pédagogique en **Machine Learning** visant à entraîner un modèle de **régression logistique** pour résoudre un problème de classification binaire.  
Il est conçu pour comprendre les étapes fondamentales de la construction, de l'entraînement et de l'évaluation d'un modèle de régression logistique.

## Objectifs pédagogiques

- Comprendre les principes de la régression logistique  
- Apprendre à prétraiter les données pour la classification binaire  
- Construire et entraîner un modèle de régression logistique  
- Évaluer les performances du modèle sur des données de test  

## Prérequis

- Python ≥ 3.10  
- Environnement Jupyter (ou autre IDE compatible)  
- Bibliothèques de Machine Learning (par exemple, scikit-learn, pandas, matplotlib) 

## Installation

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/Sengsathit/Teaching-ML_demo_logistic_regression.git
   cd Teaching-ML_demo_logistic_regression
   ```

2. Créez un environnement virtuel (optionnel mais recommandé) :

   ```bash
   python -m venv venv
   source venv/bin/activate  # ou .\venv\Scripts\activate sous Windows
   ```

3. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

4. Lancez le notebook :

   ```bash
   jupyter notebook
   ```

## Structure du projet

- `demo_logistic_regression.ipynb` : notebook principal illustrant le processus de régression logistique  
- `notions.ipynb` : notebook complémentaire expliquant les concepts théoriques  
- `data/` : dossier contenant les données utilisées pour l'entraînement et le test  
- `img/` : ressources visuelles pour la présentation  
- `models/` : dossier pour enregistrer les modèles entraînés  
- `requirements.txt` : liste des dépendances Python nécessaires  