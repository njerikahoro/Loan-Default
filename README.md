# Loan-Default
This project aims to predict the likelihood that a loan applicant will default on their loan using historical customer and loan data. It was developed as part of the Loan Default Prediction Challenge hosted on Zindi Africa.

#Approach
1.	Data Cleaning & Preprocessing
o	Handled missing values and duplicates
o	Encoded categorical variables using Label Encoding / One-Hot Encoding
o	Scaled numerical features
o	Removed irrelevant or highly correlated features
2.	Exploratory Data Analysis (EDA)
o	Analyzed class imbalance between defaulters and non-defaulters
o	Visualized key correlations and feature importance
o	Derived insights from variables such as income, loan amount, and credit history
3.	Modeling
o	Tested multiple algorithms: Logistic Regression, Random Forest, XGBoost, and LightGBM
o	Tuned hyperparameters using cross-validation
o	Evaluated models using metrics like Accuracy, F1-Score, and AUC-ROC
4.	Final Model
o	Selected the model with the best balance between interpretability and performance
o	Exported the trained model for predictions on the test dataset

