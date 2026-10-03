# Iris Flower Classification

## Project Overview

This project is developed as part of the **CodeAlpha Data Science Internship – Task 1**.

The objective of this project is to build a machine learning classification model that can predict the species of an Iris flower based on its sepal and petal measurements.

The project uses the famous **Iris dataset** available through Scikit-learn.

## Problem Statement

The goal is to classify Iris flowers into three different species:

* Setosa
* Versicolor
* Virginica

The classification is performed using four flower measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Dataset

The Iris dataset contains:

* **150 samples**
* **4 input features**
* **3 target classes**

Each species contains 50 samples.

The dataset was loaded using the `load_iris()` function from Scikit-learn.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

The project follows these steps:

1. Import required libraries
2. Load the Iris dataset
3. Create a Pandas DataFrame
4. Understand the dataset
5. Check for missing values
6. Perform Exploratory Data Analysis (EDA)
7. Visualize feature relationships
8. Analyze feature correlations
9. Separate features and target
10. Split the data into training and testing sets
11. Apply feature scaling
12. Train multiple classification models
13. Evaluate model performance
14. Compare model accuracies
15. Predict the species of a new Iris flower

## Exploratory Data Analysis

The following visualizations were performed:

* Species distribution
* Sepal length boxplot
* Petal length boxplot
* Pairplot
* Correlation heatmap

The EDA showed that petal-related features provide strong information for distinguishing between Iris species.

## Machine Learning Models

Five classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)

## Model Results

| Model               |   Accuracy |
| ------------------- | ---------: |
| Logistic Regression |     93.33% |
| Decision Tree       |     93.33% |
| Random Forest       |     90.00% |
| KNN                 |     93.33% |
| SVM                 | **96.67%** |

Among the tested models, **SVM achieved the highest accuracy of 96.67%** on the test dataset.

## Final Prediction

A new Iris flower sample was provided to the trained SVM model:

* Sepal Length: 5.1 cm
* Sepal Width: 3.5 cm
* Petal Length: 1.4 cm
* Petal Width: 0.2 cm

The model predicted:

**Setosa**

## Conclusion

This project demonstrates a complete machine learning classification workflow using the Iris dataset.

Exploratory Data Analysis helped understand the distribution and relationships between the features. Multiple classification algorithms were then trained and evaluated.

The **Support Vector Machine (SVM)** model achieved the highest test accuracy of **96.67%** among the models tested.

This project provided practical experience in data preprocessing, exploratory data analysis, machine learning model training, evaluation, comparison, and prediction.

## Project Structure

```text
CodeAlpha_IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── iris.csv
├── requirements.txt
└── README.md
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-link>
```

### 2. Navigate to the project folder

```bash
cd CodeAlpha_IrisFlowerClassification
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Iris_Flower_Classification.ipynb
```

Run the notebook cells from top to bottom.

## Internship

**CodeAlpha Data Science Internship**

Task 1: **Iris Flower Classification**

## Author

**Elaiyarasi E**

B.E. Computer Science and Engineering
Aarupadai Veedu Institute of Technology (AVIT), Chennai
