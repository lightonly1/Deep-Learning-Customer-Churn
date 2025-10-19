# Customer Churn Prediction using Deep Learning (Keras & TensorFlow)

## Project Overview
This project focuses on predicting customer churn in the telecom sector using a Deep Learning model built with Keras and TensorFlow. The primary objective is to identify customers who are likely to discontinue services, enabling proactive retention strategies.

---

## Model Performance
| Metric        | Score |
|---------------|--------|
| Accuracy      | 80.8% |
| ROC–AUC Score | 0.857 |

These scores indicate strong model generalization and a high capability to distinguish between churn and non-churn customers.

---

## Business Insights
- Customers on month-to-month contracts exhibit higher churn rates.
- Short-tenure customers are less loyal, highlighting the importance of early engagement.
- Fiber-optic service users show higher churn risk, possibly due to cost or service quality issues.
- Long-term contracts and automatic payment methods significantly improve customer retention.

---

## Tech Stack
**Programming Language:** Python  
**Libraries & Tools:** TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
**Environment:** Jupyter Notebook  
**Dataset:** `customer_churn_.csv`

---

## Model Architecture
- Input Layer  
- Two Dense Hidden Layers with ReLU activation  
- Dropout Layers to prevent overfitting  
- Output Layer with Sigmoid activation  
- Optimizer: Adam  
- Loss Function: Binary Crossentropy

---

## Project Structure
Deep-Learning-Customer-Churn/
│
├── Customer_Churn_Prediction_using_Deep_Learning_(Keras_&TensorFlow).ipynb
├── customer_churn.csv
├── README.md
└── .gitignore


---

## How to Run the Project
1. Clone the repository:
git clone https://github.com/lightonly1/Deep-Learning-Customer-Churn.git
2. Install dependencies:
pip install -r requirements.txt
3. Launch the Notebook:
jupyter notebook
4. Run all cells in the Notebook file.

---

## Future Enhancements
- Hyperparameter tuning with GridSearch or Bayesian Optimization  
- Model deployment using Flask or Streamlit  
- Use SHAP or LIME for model interpretability  
- Save and load the trained model (`model.h5`)

---

## Author
**Krit Prakash**  
Machine Learning Engineer | NLP Specialist  
GitHub: https://github.com/lightonly1  
LinkedIn: https://www.linkedin.com/in/krit-prakash-9a32a1246/
