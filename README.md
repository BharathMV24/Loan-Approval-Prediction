# Loan Approval Prediction System

## Project Overview
This project leverages Machine Learning to automate the loan approval process for a banking institution. By analyzing key applicant features—such as credit history, income, marital status, and education—the model predicts whether an applicant is eligible for a loan, helping banks streamline their decision-making process.

## Key Features
- **Data Preprocessing:** Handled missing values and encoded categorical variables.
- **Exploratory Data Analysis (EDA):** Visualized feature correlations using heatmaps and bar plots to identify significant predictors.
- **Model Comparison:** Evaluated four classification algorithms:
  - Random Forest Classifier (Best Performer)
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Classifier (SVC)
- **Performance:** Achieved ~82% accuracy using the Random Forest model.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment:** Jupyter Notebook / Anaconda

## Results
The Random Forest Classifier provided the highest accuracy for predicting loan approval status, demonstrating that ensemble techniques are effective for this classification task.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Run the notebook in your environment.
