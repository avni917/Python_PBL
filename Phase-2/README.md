# 📌 Phase 2: Model Training and Evaluation

Overview:
In this phase, the preprocessed dataset is used to train and evaluate multiple machine learning models.

 Steps Performed:

 1. Data Loading
- Loaded the preprocessed dataset from Phase 1.

 2. Feature and Label Separation
- Split dataset into features (X) and target variable (Label).

 3. Train-Test Split
- Data split into training and testing sets (80:20 ratio).

 4. Feature Scaling
- Applied StandardScaler to normalize the data.
- Scaling performed after splitting to avoid data leakage.

 5. Model Training
Trained multiple models:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tress Classifier
- Random Forest Classifier

 6. Hyperparameter Tuning
- Used Elbow Method to find optimal value of K for KNN.

 7. Model Evaluation
- Evaluated models using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
    
Output
- Trained models
- Performance comparison of models
- Elbow method graph

Conclusion
Multiple models were trained and evaluated

