# Diabetes-Prediction-ML-Project
📌 Problem Statement
Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in better management and prevention.  

This project uses the Pima Indians Diabetes Dataset to predict whether a patient is likely to have diabetes based on medical measurements such as:
glucose level, BMI, and blood pressure and pregnancies.
Outcome (0 = No Diabetes, 1 = Diabetes)

**Source:** [Pima Indians Diabetes Database - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  


🔧 Tech Stack:
•	Python | Pandas| Scikit-learn  | Matplotlib | Jupyter Notebook | joblib

🧠 Model:
•	Algorithm: Random Forest Classifier, Decision Tree Classifier
•	Metrics: Accuracy, Precision, Recall, F1-Score

🔍 Project Steps
1. Importing necessary libraries
   
2. Data Loading & Exploration (EDA)
   - Checking for missing values,duplicates
   - Summarise statistics

3. Data Preprocessing
   - Handling missing/zero values
   -Replacing NaN's with statistic values

4.Splitting data
  -splitting data before training model
  -80-20 split (80% for training data and 20% for testing data)
   
5. Model Building
   - Decision Tree Classifier
   - Random Forest Classifier
   
6. Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

7.Saving model
  -Joblib 


🚀 How to Use:
1.	Clone the repo.
2.	Install dependencies: pip install -r requirements.txt.
3.	Run the Diabetes_Prediction_Model.ipynb notebook to test the model with sample data.





