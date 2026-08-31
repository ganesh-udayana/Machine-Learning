# Machine Learning Practice – Week 3 to Week 7

This repository contains my **Machine Learning practice work from Week 3 to Week 7**, covering data preprocessing, exploratory data analysis, regression, and classification algorithms using Python and Scikit-learn.

## 📚 Topics Covered

* Data preprocessing and cleaning
* Handling missing values
* Duplicate and outlier detection
* Label encoding and feature scaling
* Feature engineering
* Data visualization
* Train-test splitting
* Linear Regression
* Polynomial Regression
* Decision Tree Classification
* K-Nearest Neighbors (KNN)
* Model evaluation using different metrics

## 📂 Repository Structure

| File          | Topic                 | Main Concepts                                                         |
| ------------- | --------------------- | --------------------------------------------------------------------- |
| `Week3.ipynb` | Data Preprocessing    | Missing values, encoding, scaling, feature engineering, visualization |
| `Week4.ipynb` | Linear Regression     | Train-test split, Linear Regression, MAE, MSE, RMSE, R²               |
| `Week5.ipynb` | Polynomial Regression | Polynomial features, model training, evaluation, visualization        |
| `Week6.ipynb` | Decision Tree         | Classification, Label Encoding, Confusion Matrix, ROC-AUC             |
| `Week7.ipynb` | K-Nearest Neighbors   | Standardization, KNN, Classification Report, ROC-AUC                  |

## 🧠 Week 3 – Data Preprocessing

Worked with a passenger satisfaction dataset and performed:

* Dataset inspection using `head()`, `shape()`, `info()`, and `describe()`
* Missing value handling
* Duplicate record checking
* Label encoding
* Min-Max scaling
* Feature engineering
* Outlier detection
* Data visualization
* Customer satisfaction analysis

### Libraries Used

* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📈 Week 4 – Linear Regression

Worked with a **Student Scores** dataset to understand the relationship between study hours and scores.

### Steps

* Loaded and explored the dataset
* Checked missing values and outliers
* Prepared features and target
* Split data into training and testing sets
* Built a Linear Regression model
* Generated predictions
* Evaluated the model

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

A regression line was also visualized using Matplotlib.

---

## 🍦 Week 5 – Polynomial Regression

Worked with an **Ice Cream Sales** dataset to model the relationship between temperature and ice cream sales.

### Steps

* Dataset exploration and preprocessing
* Duplicate and outlier checking
* Feature-target separation
* Train-test split
* Polynomial feature generation
* Polynomial Regression model
* Prediction and evaluation
* Visualization of the regression curve

### Evaluation Metrics

* MAE
* MSE
* RMSE
* R² Score

---

## 🚗 Week 6 – Decision Tree Classification

Worked with the **Car Evaluation** dataset using a Decision Tree Classifier.

### Steps

* Dataset exploration
* Feature identification
* Column preprocessing
* Label encoding
* Feature-target separation
* Train-test split
* Decision Tree model using **Entropy**
* Test predictions
* Model evaluation
* Decision tree visualization
* ROC curve analysis

### Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report
* ROC-AUC Score

---

## 🐧 Week 7 – K-Nearest Neighbors (KNN)

Worked with a **Penguins** dataset to classify penguin species using KNN.

### Steps

* Dataset exploration
* Removed unnecessary columns
* Handled missing values
* Checked duplicate records
* Examined numerical features using boxplots
* Label encoded the target
* Separated features and target
* Train-test split
* Standardized features using `StandardScaler`
* Built a KNN classifier with `k = 5`
* Generated predictions
* Evaluated classification performance
* Generated confusion matrix and ROC curves

### Evaluation Metrics

* Accuracy
* Classification Report
* Confusion Matrix
* ROC-AUC Score

---

## 🛠️ Technologies & Libraries

```text
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
```

## 🎯 Learning Objectives

Through these weekly exercises, I practiced:

1. Cleaning and preparing real-world datasets
2. Performing exploratory data analysis
3. Creating useful features
4. Applying data normalization and standardization
5. Building regression models
6. Building classification models
7. Evaluating machine-learning models
8. Visualizing data and model results

## 🚀 How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open any of the `Week3.ipynb` to `Week7.ipynb` notebooks and run the cells.

## 📌 Note

The notebooks were created as part of my **weekly Machine Learning learning and practice**, with each week focusing on different concepts and algorithms.
