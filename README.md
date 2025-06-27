# task4
🧠 Binary Classification with Logistic Regression
This project demonstrates the process of solving a binary classification problem using a logistic regression model. The dataset used is a medical dataset containing diagnostic features, and the target is to classify cases as either Malignant (M) or Benign (B).

📌 Objective
To load and preprocess a binary classification dataset.
Split the data into training and testing sets.
Standardize the feature values.
Train a logistic regression model.
Evaluate model performance using key classification metrics.
Plot and analyze the ROC curve.
Tune classification threshold and explain the role of the sigmoid function.

🗂️ Dataset
The dataset contains features computed from digitized images of breast mass samples, including:
Mean, standard error, and worst values of features like radius, texture, perimeter, area, smoothness, etc.
Target column: diagnosis (M for Malignant, B for Benign)

⚙️ Workflow Steps
Data Preprocessing:
Remove unnecessary columns like id, Unnamed: 32.
Encode target variable (M → 1, B → 0).
Standardize features using StandardScaler.

Train-Test Split: Data split into 80% training and 20% testing using train_test_split.

Model Training:Fit a LogisticRegression model on the training data.

Evaluation Metrics:
Confusion Matrix
Precision
Recall
ROC-AUC Score
ROC Curve Visualization

Threshold Tuning & Sigmoid Function:
Use predicted probabilities to adjust classification threshold.
Explain how the sigmoid function outputs probabilities between 0 and 1, enabling threshold tuning.

📊 Results
ROC-AUC Score typically > 0.95
Well-balanced precision and recall for cancer classification
Clear ROC curve indicating effective class separation
