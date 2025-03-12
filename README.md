# Credit-Card-Fraud-Detection-Machine-learning-project
This project successfully detects fraud transactions with a high recall score, meaning it catches most fraud cases. By using data balancing, hyperparameter tuning, and a strong machine learning model, we have improved the detection of fraudulent activities.

Project Overview
This project is designed to detect fraudulent transactions using machine learning techniques. We use a dataset containing credit card transactions and train models to identify which transactions are genuine and which are fraudulent.

The goal is to increase accuracy while ensuring we catch as many fraud cases as possible. We use techniques like Random Forest Classifier, GridSearchCV, and SMOTE to improve performance.

---

Dataset
We use a dataset that contains credit card transactions. It has:
- Normal Transactions (Class = 0)
- Fraud Transactions (Class = 1)

Since fraud cases are rare, we balance the data using SMOTE (Synthetic Minority Over-sampling Technique).

Technologies & Libraries Used
This project is implemented in Python using the following libraries:
pandas: Data manipulation and analysis 
numpy: Handling numerical data 
matplotlib & seaborn: Data visualization
scikit-learn: Machine learning algorithms 
imbalanced-learn: Handling imbalanced data with SMOTE 

How It Works

Step 1: Data Preprocessing
1. Load the dataset using pandas.
2. Check for missing values and clean the data.
3. Balance the dataset using SMOTE.

Step 2: Model Training
1. Split the data into training (75%) and testing (25%) sets.
2. Train a Random Forest Classifier to detect fraud.
3. Use GridSearchCV to find the best model settings (hyperparameters).

Step 3: Model Evaluation
1. Predict transactions on the test data.
2. Generate a confusion matrix to check performance.
3. Print accuracy, precision, recall, and F1-score.


Results & Improvements
We used Random Forest Classifier with optimized settings to improve fraud detection. The best model was selected using GridSearchCV, and it achieved better recall, meaning it caught more fraud cases than before.

To further improve accuracy, we:
- Used SMOTE to balance the dataset.
- Tuned hyperparameters using GridSearchCV.
- Focused on recall to catch more fraud cases.

 Future Improvements
- Try different machine learning models (e.g., XGBoost, Neural Networks).
- Use feature engineering to create better input data.
- Deploy the model using a web app for real-time fraud detection.

Conclusion
This project successfully detects fraud transactions with a high recall score, meaning it catches most fraud cases. By using data balancing, hyperparameter tuning, and a strong machine learning model, we have improved the detection of fraudulent activities.


