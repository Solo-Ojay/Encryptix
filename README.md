# Encryptix Machine Learning Internship Tasks

This repository contains code and documentation for three distinct machine learning tasks:

1. **Credit Card Fraud Detection**
2. **Customer Churn Prediction**
3. **Spam SMS Detection**

## Task 1: Credit Card Fraud Detection

### Overview
The Credit Card Fraud Detection project focuses on identifying fraudulent transactions in credit card data. It involves preprocessing, feature engineering, model training, and performance evaluation.

### Tasks
1. **Data Preprocessing**:
   - Loaded and explored the credit card dataset from [Kaggle](https://www.kaggle.com/datasets/kartik2112/fraud-detection).
   - Handled missing values and encoded categorical variables.
   - Balanced the dataset using upsampling.

2. **Feature Engineering**:
   - Created features from categorical data using `LabelEncoder`.
   - Dropped unnecessary columns and split data into features and target variables.

3. **Model Training and Evaluation**:
   - Trained a `RandomForestClassifier` on the training data.
   - Evaluated model performance using metrics such as accuracy, precision, recall, F1-score, ROC AUC, and PR AUC.
   - Visualized confusion matrix, ROC curve, and precision-recall curve.

### Files
- [Credit Card Fraud Detection](https://github.com/Solo-Ojay/Encryptix/blob/main/Encryptix%20Task%202%20(2).ipynb): Jupyter notebook containing code and analysis for credit card fraud detection.

## Task 2: Customer Churn Prediction

### Overview
The Customer Churn Prediction project is aimed at predicting whether a customer will leave a service. This project involves data preprocessing, feature engineering, and model training.

### Tasks
1. **Data Preprocessing**:
   - Loaded and explored the customer churn dataset from [Kaggle](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction).
   - Handled missing values and dropped unnecessary columns.
   - Encoded categorical features using one-hot encoding.

2. **Feature Scaling and Balancing**:
   - Scaled numerical features using `MinMaxScaler`.
   - Used SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance.

3. **Model Training and Evaluation**:
   - Trained a `RandomForestClassifier` on the resampled training data.
   - Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.

### Files
- [Customer Churn Prediction](https://github.com/Solo-Ojay/ENCRYPTIX/blob/main/Encryptix%20Task%203.ipynb): Jupyter notebook containing code and analysis for customer churn prediction.
  
## Task 3: Spam Detection

### Overview
The Spam Detection project aims to classify SMS messages as either "ham" (legitimate) or "spam". This involves preprocessing text data, training a machine learning model, and making predictions on new messages.

### Tasks
1. **Data Preprocessing**:
   - Loaded and cleaned the SMS dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).
   - Combined and dropped unnecessary columns.
   - Converted labels to binary format (ham: 0, spam: 1).

2. **Text Vectorization**:
   - Used `CountVectorizer` to convert text data into numerical feature vectors.

3. **Model Training and Evaluation**:
   - Trained a `MultinomialNB` (Naive Bayes) model on the training data.
   - Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.
   - Made predictions and classified individual SMS messages.

4. **Interactive Prediction**:
   - Implemented a simple user interface to input SMS text and predicted if it's ham or spam, [Spam Detector](https://blank-app-ngbvl7fzyb.streamlit.app/).

### Files
- [Spam SMS Detection](https://github.com/Solo-Ojay/Encryptix/blob/main/Encryptix%20Task%204%20(1).ipynb): Jupyter notebook containing code and analysis for spam detection.

## Installation

To run these notebooks, you will need Python and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. **Credit Card Fraud Detection**: Open [Credit Card Fraud Detection](https://github.com/Solo-Ojay/Encryptix/blob/main/Encryptix%20Task%202%20(2).ipynb), and follow the steps for data processing, model training, and evaluation.
2. **Customer Churn Prediction**: Open [Customer Churn Prediction](https://github.com/Solo-Ojay/ENCRYPTIX/blob/main/Encryptix%20Task%203.ipynb), and execute the code for preprocessing, feature engineering, and model evaluation.
3. **Spam Detection**: Open [Spam SMS Detection](https://github.com/Solo-Ojay/Encryptix/blob/main/Encryptix%20Task%204%20(1).ipynb) in Jupyter Notebook, follow the steps for preprocessing, training, and predicting spam messages.
