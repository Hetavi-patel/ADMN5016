# ADMN5016

# 🧠 Logistic Regression on Advertising Data

## 📁 Project Structure
```
├── .gitignore                           # Files and folders to be ignored by Git
├── ADMN5016 Week 4 Logistic Regression-Solutions.ipynb   # Jupyter notebook with full analysis
├── README.md                           # Project overview and instructions
├── advertising.csv                     # Dataset used for analysis
└── requirements.txt                    # Python package dependencies
```

---

## 📌 Project Overview

This project showcases the application of **logistic regression** on an advertising dataset to analyze the relationship between marketing spend across different media and the likelihood of consumer response (e.g., purchase). The notebook walks through the entire workflow: data loading, visualization, model fitting, and evaluation.

This analysis was conducted as part of the **ADMN5016: Data Analytics** course.

---

## 📊 Dataset

**File**: `advertising.csv`

This CSV file includes:
- `TV`: TV advertising budget
- `Radio`: Radio advertising budget
- `Newspaper`: Newspaper advertising budget
- `Sales`: Sales value (used or transformed into binary outcome for logistic regression)

---

## 📘 Notebook: Logistic Regression

**File**: `ADMN5016 Week 4 Logistic Regression-Solutions.ipynb`

This Jupyter notebook contains:
- Exploratory Data Analysis (EDA)
- Data transformation and binary classification target
- Logistic Regression using `statsmodels` and `sklearn`
- Model performance evaluation:
  - Confusion Matrix
  - Accuracy
  - ROC Curve & AUC
- Interpretation of coefficients

---

## 🔧 requirements.txt

To install necessary packages:
```bash
pip install -r requirements.txt
```

Example contents:
```
pandas
matplotlib
seaborn
scikit-learn
statsmodels
```

---

## 🧠 Learning Outcomes

- Understand logistic regression and its application in marketing analytics
- Learn to evaluate binary classification models
- Apply statistical thinking to business problems
- Use Python libraries for data analysis and machine learning

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. Create and activate a virtual environment (optional but recommended)

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook "ADMN5016 Week 4 Logistic Regression-Solutions.ipynb"
   ```

---

## 👤 Author

**Hetavi Patel**  
📫 hetavipatel3407@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com)

---

## ⚠️ Disclaimer

This project is for academic and educational purposes only. The dataset and analysis are based on course materials and may include assumptions or synthetic transformations for demonstration.
