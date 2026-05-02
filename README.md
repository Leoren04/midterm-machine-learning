# Midterm: Machine Learning End-to-End Pipeline

## 1. Purpose of the Repository
This repository contains the code and resources for the midterm assignment of the Machine Learning class. It demonstrates end-to-end data pipelines ranging from data preprocessing and handling missing values to model evaluation using traditional Machine Learning algorithms.

## 2. Brief Overview of the Project
This repository covers three distinct practical tasks simulating real-world data science problems using Machine Learning techniques:
*   **Task 1: Fraud Detection (Classification)** - Predicting whether online transactions are fraudulent.
*   **Task 2: Song Year Prediction (Regression)** - Predicting the release year of songs based on computed audio features.
*   **Task 3: Customer Clustering (Unsupervised Learning)** - Grouping credit card users based on their spending and payment behaviors.

## 3. Description of the Models and Matrix Results Used
*   **Classification (Fraud Detection):** 
    *   **Model:** Random Forest Classifier.
    *   **Metrics:** ROC-AUC Score, Classification Report (Precision, Recall, F1-Score).
*   **Regression (Song Year Prediction):**
    *   **Model:** Random Forest Regressor.
    *   **Metrics:** Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R-squared (R²).
*   **Clustering (Customer Behavior):**
    *   **Model:** K-Means Clustering.
    *   **Metrics:** Inertia (Elbow Method for optimal K), Silhouette Score.

## 4. How to Navigate Through the GitHub/Notebooks
1. Ensure you have the required datasets placed in the same directory as the notebooks (datasets are not uploaded due to GitHub size restrictions).
    *   `train_transaction.csv` & `test_transaction.csv` (for Task 1)
    *   `midterm-regresi-dataset.csv` (for Task 2)
    *   `clusteringmidterm.csv` (for Task 3)
2. Install required dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open the `.ipynb` files sequentially (e.g., `Fraud_Detection.ipynb`, `Song_Year_Prediction.ipynb`, `Customer_Clustering.ipynb`) in Jupyter Notebook or JupyterLab.
4. Run the cells from top to bottom. The `task1_submission.csv` contains the final predicted probabilities for Task 1.

## 5. Identification
*   **Name:** Rakha Primindra Danuatmaja
*   **Class:** TK-46-GAB
*   **NIM:** 1103223001
