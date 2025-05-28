# Purchase Prediction using Logistic Regression

This project uses a Logistic Regression model to predict whether a user will purchase a product based on features such as age, estimated salary, and gender. The model is trained and evaluated using a clean machine learning pipeline built with scikit-learn.

## 📁 Project Structure

- `MLmodel.ipynb`: Jupyter Notebook containing all steps from data preprocessing to model evaluation and visualization.

## 📊 Dataset

The dataset is sourced from Kaggle and includes user data related to social network ads:

[Social Network Ads Dataset - Kaggle](https://www.kaggle.com/datasets/dragonheir/logistic-regression/code)

## ⚙️ Features and Target

- **Features**:
  - `Age` (numerical)
  - `EstimatedSalary` (numerical)
  - `Gender` (categorical)

- **Target**:
  - `Purchased` (0 = No, 1 = Yes)

## 🔍 Preprocessing

- Numerical features scaled with `StandardScaler`
- Categorical features one-hot encoded using `OneHotEncoder`
- Train-test split with 75% training and 25% testing

## 📈 Model

- **Algorithm**: Logistic Regression
- **Framework**: Scikit-learn
- **Evaluation Metrics**:
  - Accuracy
  - Confusion Matrix
  - Classification Report

## 📊 Results

The model's performance is visualized using a confusion matrix, and its effectiveness is summarized using a classification report.

## 🚀 How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib

