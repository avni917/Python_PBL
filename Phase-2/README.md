 Phase 2: Model Training
🔹 Overview
In this phase, the preprocessed dataset is used to train a machine learning model. The focus is on preparing the data for training, selecting optimal parameters, and building the model.

🔹 Steps Performed:

1. Load Preprocessed Dataset:
The cleaned dataset from Phase 1 is loaded for training.

2. Feature and Label Separation:
Features (X) and target variable (Label) are separated.

3. Train-Test Split:
Dataset is split into training and testing sets using an 80:20 ratio.

4. Feature Scaling:
Standardization is applied using StandardScaler.
Scaling is performed after splitting to avoid data leakage.

5. Optimal K Selection (Elbow Method):
Different values of K (1 to 20) are tested.
Error rate is calculated for each K.
The optimal K value is selected based on minimum error.

6. Model Training:
K-Nearest Neighbors (KNN) algorithm is used.
Final model is trained using the optimal K value.

🔹 Output:
Trained KNN model
Elbow method graph for K selection

🔹Note: Model evaluation (accuracy, confusion matrix, etc.) will be performed in Phase 3.
