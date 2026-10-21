# regression-lineaire-labo3
régression linéaire avec scikit-learn
# Laboratoire 3 : Régression linéaire

Trois activités de régression avec Python et scikit-learn.

## Contenu
1. **Âge → revenu** : régression linéaire simple
2. **Demande de vélos** : régression simple vs multiple (Bike Sharing)
3. **Besoins énergétiques** : prédiction du chauffage et du refroidissement (Energy Efficiency)

## Données
- Bike Sharing Dataset : https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset
- Energy Efficiency : https://archive.ics.uci.edu/dataset/242/energy+efficiency

Pour exécuter le notebook, télécharge `day.csv` et `ENB2012_data.xlsx` et place-les dans le même dossier.

## Bibliothèques
numpy, pandas, matplotlib, scikit-learn, openpyxl

## Résultats principaux
- Activité 1 : R² = ... (pente = ..., intercept = ...)
- Activité 2 : R² simple = ... / R² multiple = ...
- Activité 3 : R² chauffage = ... / R² refroidissement = ...




ENGLISH
- Three regression activities using Python and scikit-learn.

Contents
Age → income: simple linear regression on a small hand-written dataset
Bike rental demand: simple vs. multiple linear regression (Bike Sharing dataset)
Building energy needs: predicting heating and cooling loads (Energy Efficiency dataset)
Data
Bike Sharing Dataset: https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset
Energy Efficiency: https://archive.ics.uci.edu/dataset/242/energy+efficiency

To run the notebook, download day.csv and ENB2012_data.xlsx from the links above and place them in the same folder as the notebook.

Note: the Energy Efficiency data comes from simulated building configurations, not from real consumption measurements.

Requirements

numpy, pandas, matplotlib, scikit-learn, openpyxl

pip install numpy pandas matplotlib scikit-learn openpyxl notebook
Methods
Scatter plots to explore relationships between variables
LinearRegression from scikit-learn (simple and multiple)
80/20 train/test split (random_state=42) to evaluate predictions on unseen data
Metrics: MSE (mean squared error) and R²
Main results
Activity 1: R² = ... (slope = ..., intercept = ...)
Activity 2: R² simple = ... / R² multiple = ...
Activity 3: R² heating = ... / R² cooling = ...
Limitations
In Activity 1, R² is computed on the training data, so it does not measure how well the model generalizes.
A correlation between two variables does not prove that one causes the other.
Activity 3 relies on simulated buildings only, with a strictly linear model and a single train/test split.
