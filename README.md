# Aqueous Solubility Prediction Using Hybrid Molecular Representations
This project focuses on predicting aqueous solubility (logS) of chemical compounds using machine learning models built on hybrid molecular representations. We combine Morgan fingerprints with physicochemical descriptors to improve predictive performance over single-representation approaches.

The system is trained on approximately 9,980 compounds from ESOL and AqSolDB datasets and demonstrates strong predictive accuracy using ensemble learning methods.

# Key Features:
*Hybrid molecular feature engineering using:
-Morgan fingerprints (circular fingerprints)
-Physicochemical descriptors (RDKit)
*Machine learning models:
-Random Forest
-XGBoost
*Performance improvement over baseline descriptor-only and fingerprint-only models
*Interactive web app for real-time prediction from SMILES input
*Poster presentation at the 2026 Strasbourg Summer School on Chemoinformatics

# Results:
Model	Performance
Best Model (RF / XGBoost ensemble)	R² = 0.783
Error	RMSE = 1.116 logS

#The hybrid feature approach significantly outperformed single-representation baselines.

#Tech Stack:
*Python
*RDKit
*scikit-learn
*XGBoost
*Random Forest
*Streamlit
*Web Application

A Streamlit-based interface allows users to:

Input SMILES strings
Generate molecular features
Predict aqueous solubility (logS) instantly

#Collaboration

This project was developed collaboratively by:

*Vasudha Pai
*Mirna Ashri
*Patrick Laborbe

#Acknowledgements

ESOL dataset contributors
AqSolDB database team
RDKit development community
Strasbourg Summer School on Chemoinformatics (2026)

#Future Work
*Hyperparameter optimization with Bayesian search
*Extend the scope of the datasets used
*Deep learning models (Graph Neural Networks)
*Uncertainty quantification for predictions
*Deployment as a cloud-based API
