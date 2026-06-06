# 🔐 Network Intrusion Detection System (NIDS)
### ML-based Cybersecurity Project | AI/ML PBL

## 📌 Project Overview

This project focuses on detecting **normal and abnormal network behavior** using Machine Learning techniques. The system analyzes network traffic data features to identify possible intrusions and improve cybersecurity monitoring.

---

## 🎯 Objectives

1. Analyze network traffic data to understand patterns
2. Identify intrusion patterns using ML classification models
3. Preprocess and prepare data for model training
4. Compare multiple ML models and select the best performer

---

## 🏆 Model Performance Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 80.50% |
| K-Nearest Neighbors (KNN) | 91.50% |
| Decision Tree | 97.33% |
| **Random Forest** ✅ | **98.17%** |

> ✅ **Random Forest was selected as the final model** based on highest accuracy, balanced performance, and fewest misclassifications on unseen data.

---

## 📂 Project Phases

### Phase 1 — Project Planning & Data Preprocessing
- Problem identification and synopsis preparation
- Dataset creation using Python
- Data organization and preprocessing
- Initial exploratory data analysis (EDA)

### Phase 2 — Model Training
- Loaded preprocessed dataset from Phase 1
- Performed train-test split (80:20 ratio)
- Applied feature scaling using **StandardScaler**
- Trained 4 ML models: KNN, Logistic Regression, Decision Tree, Random Forest
- Used **Elbow Method** to select optimal K value for KNN
- Evaluated models using accuracy score, confusion matrix, and classification report

### Phase 3 — Model Selection & Testing
- Compared performance of all 4 models
- Selected **Random Forest** as best model (98.17% accuracy)
- Tested final model on completely unseen data
- Verified predictions on:
  - ✅ Normal traffic samples
  - 🚨 Attack/intrusion samples
- Model demonstrated strong generalization and reliability

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | ML model training and evaluation |
| Jupyter Notebook | Development environment |

---

## 📁 Repository Structure

```
Python_PBL/
│
├── Phase-1/          # Data preprocessing & EDA notebooks
├── Phase-2/          # Model training notebooks
├── Phase-3/          # Model selection & testing notebooks
└── README.md
```

## 👩‍💻 Team Members

| Name |
|---|
| Avni Srivastava |
| Jigyasa Rana |

---

## 📄 License

This project was developed as part of an academic PBL (Project-Based Learning) assignment for the B.Tech AI/ML program.
