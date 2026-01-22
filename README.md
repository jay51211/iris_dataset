#  Iris Dataset Classification (Scikit-learn)

This repository contains a Jupyter Notebook project that performs **data exploration (EDA)** and **machine learning classification** using the popular **Iris dataset**.  
The notebook builds and evaluates multiple models to classify iris flowers into one of three species.

---

##  Project Overview

The Iris dataset includes **150 samples** of iris flowers with **4 numerical features**:

- Sepal length (cm)  
- Sepal width (cm)  
- Petal length (cm)  
- Petal width (cm)

Target classes (species):

- Setosa  
- Versicolor  
- Virginica  

---

##  What This Notebook Does

###  1. Data Loading
- Loads the Iris dataset using `sklearn.datasets.load_iris()`
- Converts it into a Pandas DataFrame

###  2. Data Cleaning
- Checks for:
  - missing values
  - duplicates
  - dataset info & statistics
- Removes duplicate rows (if any)

###  3. Exploratory Data Analysis (EDA)
- Grouping and counting samples per species
- Visualizations:
  - Scatter plot (petal length vs petal width, colored by species)
  - Bar chart showing class distribution

###  4. Machine Learning Models
Splits the dataset into training and testing sets, then trains models using **pipelines**:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  

Each model is evaluated using:

- Accuracy Score  
- Precision Score  
- Confusion Matrix  
- Classification Report  

---

##  Tech Stack / Libraries Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  Files in This Repository

- `iris_dataset.ipynb` → Main notebook containing EDA + ML models  

---
