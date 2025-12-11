# 📺 Global TV Shows Classification Project (2025)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Library](https://img.shields.io/badge/Library-Scikit_Learn-orange) ![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
This project aims to predict whether a TV Show will be **"Top Rated"** (Rating ≥ 8.0) or **"Standard"** based on its features such as genre, release year, and vote count. The dataset includes 2,000 global TV shows from 2025.

We applied **Data Classification** techniques and compared three different Machine Learning algorithms to find the best model.

## 📂 Dataset Info
* **Source:** Kaggle (Top Rated TV Shows Dataset - Global 2025)
* **Rows:** 2,000
* **Target Variable:** `is_top_rated` (1: High Rating, 0: Standard)
* **Key Features:** `votes`, `release_year`, `genre` (One-Hot Encoded)

## ⚙️ Methodology & Applied Models
1.  **Exploratory Data Analysis (EDA):**
    * Analyzed distributions and correlations.
    * **Statistical T-Test:** Confirmed significant difference in 'votes' between Top Rated and Standard shows ($p < 0.05$).
2.  **Preprocessing:**
    * Feature Scaling (StandardScaler).
    * One-Hot Encoding for genres.
    * Elbow Method for KNN optimization.

## 🏆 Model Performance Results

| Model | Accuracy Score | Outcome |
| :--- | :---: | :--- |
| **Logistic Regression** | **%70.17** | 🏆 **Winner** |
| **KNN (k=15)** | %69.17 | 🥈 Runner-up |
| **Naive Bayes** | %42.17 | ❌ Underperformed |

### 🔍 Key Findings
* **Naive Bayes** failed to adapt to the binary (0-1) nature of the dataset.
* **Logistic Regression** provided the best interpretability and accuracy.
* **Animation** genre and high **Vote Counts** are the strongest indicators of a "Top Rated" show.

## 📊 Visualizations
*(You can see detailed charts including Confusion Matrices and ROC Curves in the notebook file.)*

## 📥 Presentation
You can view the detailed project presentation here:  
[👉 Download Project Presentation (PDF/PPTX)](./Sunum_Dosyamin_Adi.pdf)

---
*Created by [CEREN ÖZARSLAN] - 2025*
