# Kepler_Exoplanet_Analysis
This project explores NASA’s Kepler Space Telescope dataset to classify and analyze potential exoplanets. Using machine learning techniques, we preprocess, reduce dimensionality, and apply classification models to distinguish between confirmed exoplanets, candidates, and false positives.
📊 Dataset

Source: NASA’s Kepler Space Telescope (Cumulative Kepler Objects of Interest - KOI)

Size: ~9,500 celestial object observations

Features:

Planet Candidate Properties: orbital period, planetary radius, transit depth, equilibrium temperature

Stellar Properties: stellar radius, surface gravity, effective temperature, brightness

Transit Signal Parameters: signal-to-noise ratio, impact parameter

Classification Labels: CONFIRMED, CANDIDATE, FALSE POSITIVE

🔧 Workflow

Data Cleaning & Preprocessing

Removed columns with excessive missing values

Median imputation for error-related columns

Handled rows with >20% missing data

Feature Engineering

Correlation and variance analysis

Dimensionality reduction using PCA

Machine Learning Models

Random Forest → robust, feature importance insights

Support Vector Machine (SVM) → best performance with RBF kernel

Naive Bayes → lightweight baseline

Decision Tree → interpretable rules for scientific insights

🚀 Key Findings

SVM outperformed other models, capturing complex non-linear relationships in exoplanet detection.

Random Forest provided strong baseline accuracy and interpretability.

Naive Bayes was surprisingly robust with noisy data.

Decision Trees helped highlight important features for astrophysical research.

🛠️ Tech Stack

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

🌍 Impact

Kepler’s findings revolutionize our understanding of how common exoplanets are in the galaxy. By leveraging ML, this project demonstrates how computational methods can support astronomers in identifying and validating exoplanets faster and more effectively.
