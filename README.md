# SVR Analysis on Seaborn Tips Dataset

This project demonstrates a simple regression analysis using **Support Vector Regression (SVR)** applied to the `tips` dataset from the Seaborn library. The goal is to predict tip amounts based on various restaurant bill-related features, with hyperparameter tuning for model optimization.

---

## 📊 Dataset

- **Source**: `sns.load_dataset("tips")`  
- **Features Include**:
  - `total_bill`: Total bill (float)
  - `tip`: Tip amount (float)
  - `sex`: Male/Female
  - `smoker`: Yes/No
  - `day`: Day of the week
  - `time`: Lunch/Dinner
  - `size`: Number of people

---

## ⚙️ Techniques Used

- Data preprocessing:
  - One-hot encoding of categorical variables
  - Feature scaling with `StandardScaler`
- Support Vector Regression (`SVR`) from `scikit-learn`
- Hyperparameter tuning using `GridSearchCV`
- Exploratory Data Analysis using `seaborn` and `matplotlib`

---

## 📁 Files

- `svr_tips_analysis.ipynb` – Jupyter notebook with full analysis
- `requirements.txt` – Project dependencies
- `README.md` – This file

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/anirudh1414/svr-tips-analysis.git
   cd svr-tips-analysis
