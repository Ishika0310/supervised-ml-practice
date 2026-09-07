# Mushroom Classification using Machine Learning

## Project Overview

This project uses supervised machine learning algorithms to classify mushrooms as **edible or poisonous** based on their physical characteristics.

The project follows a complete machine learning workflow, including data exploration, preprocessing, exploratory data analysis, model training, evaluation, and model comparison.

## Dataset

The dataset contains information about **8,124 mushrooms** with **22 features** describing their characteristics.

### Target Variable

- `e` = Edible
- `p` = Poisonous

## Machine Learning Workflow

The following steps were performed:

1. Problem Definition
2. Data Collection
3. Data Understanding
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Encoding
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison

## Data Preprocessing

Since the dataset contains categorical features, the following preprocessing techniques were used:

- **One-Hot Encoding** for input features
- **Label Encoding** for the target variable
- **80/20 Train-Test Split**

After one-hot encoding, the 22 input features were converted into **117 encoded features**.

## Machine Learning Models

The following classification algorithms were trained:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes
- Gradient Boosting

## Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 100% |
| Decision Tree | 100% |
| KNN | 100% |
| SVM | 100% |
| Random Forest | 100% |
| Naive Bayes | 96% |
| Gradient Boosting | 100% |

Six of the seven models achieved 100% accuracy on the test dataset, while Naive Bayes achieved 96%.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

## Tech Stack

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## Project Files

```text
mushroom-ml/
│
├── data/
│   └── mushrooms.csv
│
└── mushroom_ml.ipynb
