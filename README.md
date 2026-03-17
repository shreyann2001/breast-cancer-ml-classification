# Breast Cancer Classification using Machine Learning

## Project Overview

Breast cancer is one of the most common and life-threatening diseases affecting women worldwide. Early and accurate diagnosis plays a critical role in improving treatment outcomes and survival rates.

This project applies **supervised machine learning algorithms** to classify breast tumors as **benign or malignant** using the **Breast Cancer Wisconsin Diagnostic Dataset** from the UCI Machine Learning Repository.

The goal of this project is to **compare the performance of multiple machine learning models** and evaluate their effectiveness in medical diagnosis tasks.

---

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin Diagnostic Dataset**, available from the UCI Machine Learning Repository.

**Dataset Characteristics**

* Total instances: **569**
* Features: **30 numerical variables**
* Target variable: **Diagnosis (Malignant / Benign)**

The features describe characteristics of cell nuclei present in digitized images of breast mass samples, including:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal dimension

The dataset is clean, fully numeric, and contains **no missing values**, making it suitable for machine learning classification tasks.

---

## Machine Learning Models Used

The following supervised learning algorithms were implemented and compared:

* Logistic Regression
* Linear Discriminant Analysis (LDA)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

These models were selected because of their strong performance in classification problems and their frequent use in medical data analysis.

---

## Methodology

The project workflow includes the following steps:

1. **Data Loading**

   The dataset was accessed using the `ucimlrepo` Python module.

2. **Data Preprocessing**

   * Separation of features and target variable
   * Encoding diagnosis labels (Malignant = 1, Benign = 0)

3. **Train-Test Split**

   The dataset was divided into:

   * **80% training data**
   * **20% testing data**

4. **Feature Scaling**

   Standardization was applied using **StandardScaler** to normalize feature ranges.

5. **Model Training**

   Each classification model was trained using the **Scikit-learn** library.

6. **Model Evaluation**

   Models were evaluated using the following metrics:

   * Accuracy
   * Precision
   * Recall
   * F1-Score

---

## Results

All five machine learning models achieved strong performance in predicting breast cancer tumor classification.

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | **97.37%** |
| LDA                 | 95.61%     |
| SVM                 | 95.61%     |
| Decision Tree       | 94.74%     |
| KNN                 | 94.74%     |

**Key Insight**

Logistic Regression performed the best overall, demonstrating strong generalization ability on the dataset.

Linear models such as **Logistic Regression, LDA, and SVM** showed slightly better stability and accuracy compared to non-linear methods.

---

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Learnings

* Machine learning models can effectively assist in medical diagnosis tasks.
* Simple models such as **Logistic Regression** can perform extremely well on structured medical datasets.
* Model comparison helps identify the best algorithm for a specific dataset and problem.

---

## Future Improvements

Potential improvements for this project include:

* Hyperparameter tuning
* Cross-validation
* Ensemble learning methods
* Testing additional models such as Random Forest or Gradient Boosting
* Deploying the model as a web application

---

## Author

**Shreyan Sarkar**

Data Analyst | Python | SQL | Machine Learning | Tableau

Email: [shreyanofficial2001@gmail.com](mailto:shreyanofficial2001@gmail.com)
