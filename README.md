# Logistic Regression Project – Advertisement Click Prediction 

## Project Description

The Logistic Regression Project is a Machine Learning application that uses the Scikit-Learn, Pandas, NumPy, Matplotlib, and Seaborn libraries to predict whether an internet user will click on an advertisement.

The project uses a fake advertising dataset containing user demographics and internet usage information. The objective is to build a Logistic Regression classification model that predicts whether a user clicks on an advertisement based on their behavior and characteristics.

This project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), data visualization, model training, prediction, and performance evaluation.

The application executes once and displays analysis results and model evaluation metrics in the notebook.

---

## Features

* Load advertising dataset using Pandas
* Explore dataset structure and statistical information
* Perform Exploratory Data Analysis (EDA)
* Visualize user behavior using Seaborn and Matplotlib
* Create histograms and joint plots
* Generate pair plots for feature relationships
* Split dataset into training and testing sets
* Build a Logistic Regression classification model
* Predict advertisement clicks
* Evaluate model performance using classification metrics

---

## Concepts Used

### Python Fundamentals

* Variables
* Data structures
* Data manipulation
* Function calls
* Output display

### Pandas Concepts

* DataFrame creation
* Reading CSV files
* Data inspection using head()
* Dataset information using info()
* Statistical summary using describe()
* Data selection and filtering

### Data Visualization Concepts

* Histogram plots
* Joint plots
* Pair plots
* Feature relationship analysis
* Distribution analysis

### Machine Learning Concepts

* Supervised Learning
* Classification Problem
* Logistic Regression
* Feature Selection
* Train-Test Split
* Model Training
* Prediction
* Model Evaluation

### Scikit-Learn Concepts

* train_test_split()
* LogisticRegression()
* fit()
* predict()
* classification_report()

---

## Dataset Information

The dataset contains the following features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Ad Topic Line
* City
* Male
* Country
* Timestamp
* Clicked on Ad (Target Variable)

Target Variable:

```
Clicked on Ad
0 = Did Not Click
1 = Clicked on Advertisement
```

---

## Project Structure

```
logistic-regression-project/
│
├── advertising.csv
├── 02-Logistic Regression Project.ipynb
└── README.md
```

---

## How to Run the Project

### Requirements

* Python 3.x installed
* Pandas library installed
* NumPy library installed
* Matplotlib library installed
* Seaborn library installed
* Scikit-Learn library installed
* Jupyter Notebook installed

### Steps

1. Open terminal or Anaconda Prompt
2. Navigate to the project directory
3. Start Jupyter Notebook
4. Open the notebook file
5. Run all cells sequentially

```
jupyter notebook
```

---

## Operations Performed

```
1. Import required libraries
2. Load advertising dataset
3. Display dataset information
4. Generate statistical summary
5. Perform Exploratory Data Analysis
6. Create visualizations using Seaborn
7. Select input features and target variable
8. Split dataset into training and testing sets
9. Train Logistic Regression model
10. Predict advertisement clicks
11. Evaluate model performance using classification report
```

---

## Visualizations Created

* Age Distribution Histogram
* Area Income vs Age Joint Plot
* Daily Time Spent on Site vs Age Joint Plot
* Daily Time Spent on Site vs Daily Internet Usage Joint Plot
* Pair Plot based on Clicked on Ad category

---

## Machine Learning Workflow

```
Dataset Loading
        ↓
Exploratory Data Analysis
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Logistic Regression Model
        ↓
Prediction
        ↓
Model Evaluation
```

---

## Sample Output

```
Classification Report

Precision
Recall
F1-Score
Support

Predicted whether users clicked on advertisements based on:
- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Gender
```

---

## Edge Cases Handled

* Proper train-test data separation
* Multiple numerical features used for prediction
* Increased Logistic Regression iterations to ensure convergence
* Classification performance evaluated using multiple metrics
* Visualization used for understanding feature relationships before modeling

---

## Skills Demonstrated

* Data Cleaning and Exploration
* Exploratory Data Analysis (EDA)
* Data Visualization
* Classification Modeling
* Logistic Regression
* Machine Learning Workflow
* Model Evaluation
* Business Analytics and Consumer Behavior Analysis

---

## Author

Meet Tailor  
Data Science & ML Learner

---

## License

This project is created for learning and educational purposes only.

---

## Project Status

Completed

Last Updated: 2026
