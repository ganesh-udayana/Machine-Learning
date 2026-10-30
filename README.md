# Machine Learning Practice – Week 3 to Week 12 + Mini Project

This repository contains my **Machine Learning practice work from Week 3 to Week 12**, along with a Mini Project on **Air Quality Prediction using Machine Learning**.

The repository covers data preprocessing, exploratory data analysis, regression, classification, neural networks, clustering, hierarchical clustering, and model evaluation using Python and Scikit-learn.

Each weekly notebook focuses on understanding and implementing different machine learning algorithms using real-world and built-in datasets.

## 📚 Topics Covered

- Data preprocessing and cleaning
- Handling missing values
- Duplicate and outlier detection
- Label encoding and one-hot encoding
- Feature engineering
- Feature scaling and standardization
- Exploratory Data Analysis (EDA)
- Data visualization
- Train-test splitting
- Linear Regression
- Polynomial Regression
- Decision Tree Classification
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Perceptron
- Artificial Neural Networks (ANN)
- Multi-Layer Perceptron (MLP)
- K-Means Clustering
- Hierarchical Clustering
- Model evaluation and performance comparison
- Air Quality Prediction using CRISP-DM methodology

## 📂 Repository Structure

| File | Topic | Main Concepts |
|---|---|---|
| `Week3.ipynb` | Data Preprocessing | Missing values, encoding, scaling, feature engineering, visualization |
| `Week4.ipynb` | Linear Regression | Train-test split, Linear Regression, MAE, MSE, RMSE, R² |
| `Week5.ipynb` | Polynomial Regression | Polynomial features, model training, evaluation, visualization |
| `Week6.ipynb` | Decision Tree Classification | Classification, Label Encoding, Confusion Matrix, ROC-AUC |
| `Week7.ipynb` | K-Nearest Neighbors | Standardization, KNN, Classification Report, ROC-AUC |
| `Week_8_1.ipynb` | Support Vector Machine (SVM) | Breast Cancer dataset, One-Hot Encoding, StandardScaler, LinearSVC |
| `Week_9.ipynb` | Perceptron and MLP | MNIST dataset, Perceptron, Multi-Layer Perceptron, digit classification |
| `Week_10.ipynb` | ANN, SVM and KNN Comparison | Iris dataset, model comparison, Accuracy, Precision, Recall, F1-Score |
| `Week11_1(2).ipynb` | K-Means Clustering | Mall Customers dataset, StandardScaler, customer segmentation, cluster evaluation |
| `Week12_1(1).ipynb` | Hierarchical Clustering | Mall Customers dataset, Agglomerative Clustering, linkage, dendrogram |
| `Ganesh_ML_project.pdf` | Mini Project – Air Quality Prediction | CRISP-DM, regression models, Random Forest, model tuning, CO concentration prediction |

---

## 🧠 Week 3 – Data Preprocessing

Worked with a **Passenger Satisfaction dataset** and performed data cleaning and preprocessing.

### Steps

- Dataset inspection using `head()`, `shape()`, `info()`, and `describe()`
- Missing value handling
- Duplicate record checking
- Label encoding
- Min-Max scaling
- Feature engineering
- Outlier detection
- Data visualization
- Customer satisfaction analysis

### Libraries Used

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Week 4 – Linear Regression

Worked with a **Student Scores dataset** to understand the relationship between study hours and student scores.

### Steps

- Loaded and explored the dataset
- Checked missing values and outliers
- Prepared features and target
- Split data into training and testing sets
- Built a Linear Regression model
- Generated predictions
- Evaluated model performance
- Visualized the regression line using Matplotlib

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🍦 Week 5 – Polynomial Regression

Worked with an **Ice Cream Sales dataset** to model the relationship between temperature and ice cream sales.

### Steps

- Dataset exploration and preprocessing
- Duplicate and outlier checking
- Feature-target separation
- Train-test split
- Polynomial feature generation
- Polynomial Regression model training
- Prediction and evaluation
- Visualization of the regression curve

### Evaluation Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## 🚗 Week 6 – Decision Tree Classification

Worked with the **Car Evaluation dataset** using a Decision Tree Classifier.

### Steps

- Dataset exploration
- Feature identification
- Column preprocessing
- Label encoding
- Feature-target separation
- Train-test split
- Decision Tree model using Entropy
- Test predictions
- Model evaluation
- Decision tree visualization
- ROC curve analysis

### Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## 🐧 Week 7 – K-Nearest Neighbors (KNN)

Worked with a **Penguins dataset** to classify penguin species using KNN.

### Steps

- Dataset exploration
- Removed unnecessary columns
- Handled missing values
- Checked duplicate records
- Examined numerical features using boxplots
- Label encoded the target
- Separated features and target
- Train-test split
- Standardized features using `StandardScaler`
- Built a KNN classifier with `k = 5`
- Generated predictions
- Evaluated classification performance
- Generated confusion matrix and ROC curves

### Evaluation Metrics

- Accuracy
- Classification Report
- Confusion Matrix
- ROC-AUC Score

---

## 🩺 Week 8 – Support Vector Machine (SVM)

Worked with a **Breast Cancer dataset** to perform binary classification using a Linear Support Vector Machine.

### Steps

- Imported required Python libraries
- Loaded and explored the Breast Cancer dataset
- Inspected dataset shape, information and statistical summary
- Identified numerical and categorical features
- Checked and removed duplicate records
- Separated input features and target variable
- Encoded target labels (`Dead = 0`, `Alive = 1`)
- Split data into training and testing sets
- Applied One-Hot Encoding to categorical features
- Aligned training and testing feature columns
- Standardized features using `StandardScaler`
- Built a `LinearSVC` classification model
- Generated predictions
- Evaluated classification performance

### Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

### Main Concepts

- Support Vector Machine
- Linear Support Vector Classification
- One-Hot Encoding
- Feature Scaling
- Binary Classification

---

## 🔢 Week 9 – Perceptron and Multi-Layer Perceptron (MLP)

Worked with the **MNIST handwritten digit dataset** to classify handwritten digits using Perceptron and Multi-Layer Perceptron algorithms.

### Steps

- Imported the MNIST dataset using `fetch_openml()`
- Separated input features and target labels
- Inspected dataset shape
- Split data into training and testing sets
- Standardized features using `StandardScaler`
- Built a Simple Perceptron model
- Trained and tested the Perceptron classifier
- Built a Multi-Layer Perceptron classifier
- Used two hidden layers with 128 and 64 neurons
- Applied ReLU activation and Adam optimizer
- Generated predictions
- Compared classification performance
- Visualized handwritten digits with actual and predicted labels

### Models Used

- Perceptron
- Multi-Layer Perceptron (MLP)

### Evaluation Metrics

- Accuracy Score
- Classification Report

### Main Concepts

- Artificial Neural Networks
- Perceptron Learning
- Multi-Layer Neural Networks
- ReLU Activation Function
- Adam Optimizer
- Handwritten Digit Recognition

---

## 🌸 Week 10 – ANN, SVM and KNN Model Comparison

Worked with the **Iris dataset** to compare three different machine learning classification algorithms.

### Steps

- Loaded the Iris dataset using Scikit-learn
- Explored dataset shape
- Separated input features and target labels
- Split data into training and testing sets
- Standardized features using `StandardScaler`
- Built an Artificial Neural Network using `MLPClassifier`
- Built a Support Vector Machine using a Linear Kernel
- Built a K-Nearest Neighbors classifier with `k = 5`
- Trained all three models
- Generated predictions
- Compared model performance using evaluation metrics

### Models Used

1. Artificial Neural Network (ANN)
2. Support Vector Machine (SVM)
3. K-Nearest Neighbors (KNN)

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

### Main Concepts

- Multi-class Classification
- ANN Model Implementation
- SVM with Linear Kernel
- KNN Classification
- Model Performance Comparison
- Weighted Evaluation Metrics

---

## 🛍️ Week 11 – K-Means Clustering

Worked with the **Mall Customers dataset** to perform customer segmentation using the K-Means Clustering algorithm.

### Steps

- Imported required libraries
- Loaded and explored the Mall Customers dataset
- Inspected dataset shape and statistical information
- Encoded the Gender column
- Selected Annual Income and Spending Score as input features
- Visualized original customer data points
- Standardized features using `StandardScaler`
- Applied K-Means Clustering
- Created 5 customer clusters
- Assigned cluster labels to the dataset
- Visualized customer segments using a scatter plot
- Displayed cluster centroids
- Evaluated clustering performance

### Algorithm Used

- K-Means Clustering (`n_clusters = 5`)

### Evaluation Metrics

- Silhouette Score
- WCSS (Within-Cluster Sum of Squares / Inertia)
- Davies-Bouldin Index

### Main Concepts

- Unsupervised Learning
- Customer Segmentation
- Centroid-Based Clustering
- Feature Standardization
- Cluster Visualization
- Clustering Evaluation

---

## 🌳 Week 12 – Hierarchical Clustering

Worked with the **Mall Customers dataset** to explore Hierarchical Clustering and visualize relationships between customer groups.

### Steps

- Imported required Python libraries
- Loaded and explored the Mall Customers dataset
- Inspected dataset information and statistical summary
- Encoded the Gender column
- Selected Annual Income and Spending Score as features
- Standardized features using `StandardScaler`
- Applied hierarchical linkage using SciPy
- Used Single Linkage clustering
- Generated a hierarchical clustering dendrogram
- Visualized the hierarchical relationships between data points

### Algorithms and Techniques Used

- Hierarchical Clustering
- Agglomerative Clustering (imported for clustering practice)
- Single Linkage
- Euclidean Distance
- Dendrogram Visualization

### Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

### Main Concepts

- Unsupervised Learning
- Hierarchical Clustering
- Agglomerative Clustering
- Linkage Methods
- Dendrogram Interpretation
- Distance-Based Clustering

---

# 🚀 Mini Project – Air Quality Prediction Using Machine Learning

**Project Title:** Predicting Hourly CO Concentration Using Multi-Sensor Readings, Pollutant Levels, Weather and Time Features.

This mini project focuses on predicting hourly Carbon Monoxide (CO) concentration using the UCI Air Quality dataset and the CRISP-DM methodology.

The project implements an end-to-end machine learning pipeline to estimate CO concentration using sensor readings, pollutant measurements, weather conditions and time-based features.

### 🎯 Project Objective

- Predict hourly CO concentration (CO(GT)) in mg/m³.
- Estimate missing or unavailable CO readings using other sensor measurements.
- Identify important features influencing CO concentration.
- Compare multiple regression algorithms.
- Develop and evaluate a reliable prediction pipeline.

### 📊 Dataset

**UCI Air Quality Dataset**

The dataset contains hourly air quality measurements collected using multiple gas sensors and reference analysers.

- Original records: 9,471
- Original columns: 17
- Records after removing completely empty rows and columns: 9,357
- Records used for modelling: 7,674
- Target variable: `CO(GT)`

### Steps Performed

**1. Business Understanding**
- Defined the air quality prediction problem.
- Identified the importance of CO monitoring.
- Established the objective of predicting missing CO concentration values.

**2. Data Understanding**
- Loaded and explored the dataset.
- Examined missing values and duplicate records.
- Replaced `-200` missing-value indicators with NaN.
- Analyzed statistical summaries and feature distributions.
- Created correlation heatmaps, histograms, boxplots and scatter plots.

**3. Data Preparation**
- Removed completely empty rows and columns.
- Removed `NMHC(GT)` due to approximately 90% missing values.
- Created time-based features:
  - Hour
  - Month
  - Day of Week
- Removed rows with missing target values.
- Selected 14 input features.
- Split data chronologically into training and testing sets (80:20).
- Used median imputation and StandardScaler in a preprocessing pipeline.

**4. Model Development**

Compared six regression algorithms:

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors Regressor
- Support Vector Regression (SVR)

**5. Model Evaluation**
- Compared models using MAE, MSE, RMSE and R².
- Applied 5-fold TimeSeriesSplit cross-validation.
- Used GridSearchCV for Random Forest hyperparameter tuning.
- Analyzed actual versus predicted values.
- Examined residual distributions.
- Visualized feature importance.

**6. Deployment**
- Packaged preprocessing and the trained model into a Scikit-learn Pipeline.
- Saved the final model using `joblib`.
- Reloaded and tested the saved prediction pipeline.

### 📈 Final Model Performance

The tuned Random Forest model achieved the following test results:

| Evaluation Metric | Score |
|---|---:|
| MAE | 0.3558 |
| MSE | 0.2863 |
| RMSE | 0.5350 |
| R² Score | 0.8417 |
| Cross-Validation R² | 0.8666 |

### Best Model Parameters

- Model: Random Forest Regressor
- Number of Estimators: 100
- Maximum Depth: 20
- Minimum Samples per Leaf: 3

### Key Findings

- The PT08.S2(NMHC) sensor was the most important feature in the tuned Random Forest model.
- Benzene concentration (C6H6(GT)) was another important predictor.
- Linear Regression and Ridge Regression achieved strong test performance.
- Random Forest achieved the highest cross-validation R² among the initial models.
- The tuned Random Forest explained approximately 84% of the variation in CO concentration on the test set.
- Time-based splitting helped avoid using future observations to predict past values.

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Joblib

### Methodology

The project follows all six major CRISP-DM phases:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment

---

## 🛠️ Technologies & Libraries

The following tools and libraries were used throughout the weekly exercises and mini project:

```text
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SciPy
Joblib
```

## 🎯 Learning Objectives

Through these weekly exercises and the mini project, I practiced:

1. Cleaning and preparing real-world datasets.
2. Performing exploratory data analysis.
3. Handling missing values and duplicate records.
4. Detecting and analyzing outliers.
5. Applying encoding techniques.
6. Creating useful features.
7. Applying normalization and standardization.
8. Building regression models.
9. Implementing classification algorithms.
10. Understanding Artificial Neural Networks.
11. Applying supervised and unsupervised learning.
12. Performing customer segmentation using clustering.
13. Evaluating machine learning models using different metrics.
14. Comparing multiple machine learning algorithms.
15. Visualizing data and model results.
16. Building an end-to-end machine learning pipeline.

## 🚀 How to Run

1. Clone this repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project folder:

```bash
cd <your-repository-folder>
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy joblib jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open any weekly notebook from `Week3.ipynb` to `Week12_1(1).ipynb` and execute the cells.

**Note:** Some notebooks use datasets loaded from Google Colab paths. Make sure the corresponding CSV datasets are available and update their file paths if running locally.

For the mini project, also place the UCI Air Quality dataset in the appropriate location and update its CSV path.

## 📌 Note

These notebooks were created as part of my **weekly Machine Learning learning and practice from Week 3 to Week 12**.

Each week focuses on different machine learning concepts, algorithms, datasets and evaluation techniques. The mini project brings these concepts together through an end-to-end air quality prediction workflow using the CRISP-DM methodology.

This repository represents my continuous learning and practical experience in Machine Learning using Python and Scikit-learn.
