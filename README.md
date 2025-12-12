# 🚀 Data Science & Machine Learning Projects

Welcome to my portfolio! Here you will find my data analysis and machine learning projects, demonstrating various algorithms, statistical methods, and visualization techniques.

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Status](https://img.shields.io/badge/Status-Active-success)

## 📂 Project List

| Project Name | Domain | Key Techniques | Model Performance |
| :--- | :--- | :--- | :--- |
| **1. [Global TV Shows Classification](./TV_Shows_Classification_Project_2025.ipynb)** | 🎬 Entertainment | Random Forest, T-Test, Feature Importance | **Random Forest (%72.5)**, LogReg (%70), KNN (%69) |
| **2. [Spotify Popularity Prediction](./Spotify_Popularity_Prediction.ipynb)** | 🎵 Music / Audio | Custom Visuals (Dark Mode), RF, Pipeline | **Random Forest**, Logistic Regression |

---

## 📝 Project Details

### 1️⃣ Global TV Shows Classification (2025)
* **Goal:** Predict whether a TV show will be "Top Rated" based on genre, release year, and vote counts.
* **Updates & Methodology:**
    * **Model Upgrade:** Initial Naive Bayes model was replaced with **Random Forest** to handle the binary nature of the dataset better and improve accuracy.
    * **Comparison:** Benchmarked **Random Forest, Logistic Regression, and KNN**.
    * **Statistics:** Validated feature significance using **Statistical T-Test** ($p < 0.05$).
* **🏆 Results:**
    * **Random Forest:** **%72.50** (Winner & Best Interpretability)
    * **Logistic Regression:** %70.17 (Strong Baseline)
    * **KNN (k=15):** %69.17 (Competitive)
* **🔍 Key Insight:** Feature Importance analysis revealed that **"Vote Count"** and **"Animation Genre"** are the strongest indicators of a show's success.
* **[👉 View Code](./TV_Shows_Classification_Project_2025.ipynb)**
* **[👉 Download Project Presentation (PDF)](./Sunum_Dosyamin_Adi.pdf)**

### 2️⃣ Spotify Popularity Prediction
* **Goal:** Predict song popularity based on audio features like *danceability, energy, and acousticness*.
* **Highlights:**
    * Created a custom **Spotify-Themed Visualization Palette** (Dark Mode aesthetics).
    * Utilized **Random Forest** for feature importance analysis.
    * Includes a real-time prediction scenario script for user interaction.
* **[👉 View Code](./Spotify_Popularity_Prediction.ipynb)**

---
*Created by [CEREN ÖZARSLAN] - 2025
