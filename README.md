<div align="center">
  
# Spotify Song Attributes Classification

This repository contains a Machine Learning project focused on analyzing a Spotify song dataset to predict, based on musical attributes, whether a song will be liked by a user.

This project was developed as part of the **Machine Learning** course at the **Autonomous University of Barcelona (UAB)**.

</div>

---

### *PROJECT OBJECTIVE*
The main purpose of this project is to explore a dataset extracted from the Spotify API (known on Kaggle as *Spotify Song Attributes*, https://www.kaggle.com/datasets/geomack/spotifyclassification) and build classification models to determine user preferences based on sound characteristics.

### *DATASET*
The dataset used contains **2,017 songs** and **16 attributes** each. Features include:
- **Musical Attributes:** *acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, tempo, valence*.
- **General Information:** *duration_ms, key, mode, time_signature, song_title, artist*.
- **Target Variable:** *target* (1 = liked by the user, 0 = not liked).

### *TOOLS & LIBRARIES*
The project was developed in **Python** using a Jupyter Notebook, primarily utilizing the following libraries:
- **Data Manipulation & Analysis:** `pandas`, `numpy`, `statistics`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`
  - *Models:* Random Forest, K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree.
  - *Metrics:* ROC Curve, AUC, Precision-Recall, Accuracy, F1-Score.

### *PROJECT STRUCTURE*
The workflow in the Notebook is organized as follows:
1. **Introduction:** Case presentation and dataset overview.
2. **Exploratory Data Analysis (EDA):** Analysis to understand relationships and distributions of song features.
3. **Data Preprocessing:** Cleaning, handling null values, and feature scaling/standardization.
4. **Model Building:** Training different classification algorithms to predict the *target* variable.
5. **Evaluation & Results:** Comparative performance analysis using different metrics to find the most robust long-term solution.

> *Note: "It is important to highlight that each stage of optimization, even if it seems to slightly reduce performance at some point, helps us achieve a better understanding of the model and reach superior, more solid, and sustainable performance."*
