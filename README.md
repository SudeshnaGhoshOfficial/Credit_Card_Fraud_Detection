💳 Credit Card Fraud Detection
This project applies machine learning techniques to detect fraudulent credit card transactions using realistic, synthetic financial data. The goal is to develop classification models that can accurately distinguish between fraudulent and legitimate transactions.

📁 Dataset Information
Source: Synthetic Financial Datasets for Fraud Detection by Capital One

Files Used:

fraudTrain.csv – Training data

fraudTest.csv – Testing data

📊 Dataset Features
trans_date_trans_time: Timestamp of the transaction

merchant, category: Merchant and transaction category

amt: Transaction amount

gender, city, state, job: User demographics

dob, lat, long: Location-based features

is_fraud: Target label (1 = fraud, 0 = non-fraud)

✅ Project Highlights
Cleaned and preprocessed feature-rich fraud transaction data

Trained and evaluated three ML models:

Logistic Regression

Decision Tree

Random Forest

Visualized results using confusion matrices and ROC curves

Evaluated based on metrics: accuracy, precision, recall, F1-score, and AUC

🧠 Model Performance (on Test Data)
Model	Accuracy	Precision	Recall	F1 Score	ROC-AUC
Logistic Regression	0.9171	0.9286	0.6951	0.7951	0.8395
Decision Tree	0.9788	0.9438	0.9658	0.9547	0.9742
Random Forest	0.9391	0.9343	0.7925	0.8576	0.8879

🎯 Decision Tree Classifier performed the best, achieving high accuracy and recall, making it most effective at identifying fraudulent transactions.

📁 Project Structure
bash
Copy
Edit
├── Credit_Card_Fraud_Detection.ipynb  # Main notebook with all code and results
├── fraudTrain.csv                     # Training dataset
├── fraudTest.csv                      # Testing dataset
├── README.md                          # Project documentation
🛠 Tech Stack
Language: Python

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

Platform: Google Colab
