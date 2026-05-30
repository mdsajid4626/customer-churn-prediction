# 📉 Customer Churn Prediction

A classification project that predicts whether a customer will churn using Random Forest, with hyperparameter tuning and class imbalance handling via SMOTE.

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Random Forest (baseline) | 78.32% |
| Random Forest (after tuning) | 80.10% |

## 📁 Project Structure

```
customer-churn-prediction/
│
├── customer_churn.ipynb   # Main notebook
├── customer_churn.csv            # Dataset
└── README.md
```

## 🔍 Approach

1. **Data Cleaning** — Handled missing values and encoded categorical features
2. **EDA** — Analysed churn patterns across customer segments
3. **Class Imbalance** — Applied SMOTE to improve minority-class recall by 18%
4. **Modelling** — Trained a Random Forest classifier using Scikit-learn
5. **Hyperparameter Tuning** — Used GridSearchCV to boost accuracy from 78.32% to 80.10%
6. **Evaluation** — Assessed using confusion matrix, precision, recall, and F1-score

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier, GridSearchCV)
- imbalanced-learn (SMOTE)

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/mdsajid4626/customer-churn-prediction
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook customer_churn.ipynb
   ```

## 👤 Author

**Mohammed Sajid**  
[LinkedIn](www.linkedin.com/in/mohammmed-sajid-47b92131b) | [GitHub](https://github.com/mdsajid4626)
)