# Customer Churn Prediction using Deep Learning (Keras & TensorFlow)

## Project Overview

This project focuses on predicting customer churn in the telecom industry using a Deep Learning model built with TensorFlow and Keras. The objective is to identify customers who are likely to discontinue services, enabling businesses to implement proactive customer retention strategies.

The project includes complete data preprocessing, feature engineering, model training, evaluation, and business insight generation using Artificial Neural Networks (ANN).

---

## Problem Statement

Customer churn is one of the major challenges faced by telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to:
- Predict whether a customer will churn
- Analyze customer behavior patterns
- Generate actionable business insights
- Improve customer retention strategies

---

## Model Performance

| Metric | Score |
|---|---|
| Accuracy | 80.8% |
| ROC-AUC Score | 0.857 |

The model demonstrates strong predictive capability and good generalization performance on unseen data.

---

## Business Insights

- Customers with month-to-month contracts have higher churn probability
- Short-tenure customers are more likely to leave the service
- Fiber-optic internet users exhibit elevated churn risk
- Automatic payment methods improve customer retention
- Long-term contracts significantly reduce churn

---

## Tech Stack

### Programming Language
- Python

### Libraries & Frameworks
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Development Environment
- Jupyter Notebook

### Dataset
- `customer_churn.csv`

---

## Deep Learning Model Architecture

The Artificial Neural Network (ANN) consists of:

1. Input Layer
2. Dense Hidden Layer with ReLU Activation
3. Dropout Layer
4. Dense Hidden Layer with ReLU Activation
5. Dropout Layer
6. Output Layer with Sigmoid Activation

### Training Configuration

| Parameter | Value |
|---|---|
| Optimizer | Adam |
| Loss Function | Binary Crossentropy |
| Evaluation Metric | Accuracy |

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding and Scaling
5. Model Building using Keras
6. Model Training and Validation
7. Performance Evaluation
8. Business Insight Generation

---

## Project Structure

```bash
Deep-Learning-Customer-Churn/
│
├── Customer_Churn_Prediction_using_Deep_Learning_(Keras_&_TensorFlow).ipynb
├── customer_churn.csv
├── README.md
└── .gitignore
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/lightonly1/Deep-Learning-Customer-Churn.git
```

### 2. Navigate to the Project Directory

```bash
cd Deep-Learning-Customer-Churn
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open the notebook file:

```bash
Customer_Churn_Prediction_using_Deep_Learning_(Keras_&_TensorFlow).ipynb
```

Run all cells sequentially.

---

## Future Enhancements

- Hyperparameter tuning using Bayesian Optimization
- Model explainability using SHAP and LIME
- Deployment using Streamlit or FastAPI
- Real-time churn prediction API
- Model saving and loading using `.h5` or `.keras`
- Experiment tracking using MLflow

---

## Skills Demonstrated

- Deep Learning
- Artificial Neural Networks (ANN)
- TensorFlow & Keras
- Feature Engineering
- Classification Modeling
- Data Preprocessing
- Customer Analytics
- Business Analytics
- Model Evaluation

---

## Author

Krit Prakash  
Data Scientist | AI/ML Engineer | Data Analytics Mentor

GitHub: https://github.com/lightonly1  
LinkedIn: https://www.linkedin.com/in/krit-prakash-9a32a1246/
