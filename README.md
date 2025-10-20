# Loan-Default
This project aims to predict the likelihood that a loan applicant will default on their loan using historical customer and loan data. It was developed as part of the Loan Default Prediction Challenge hosted on Zindi Africa.

# Approach
 ##	Data Cleaning & Preprocessing
	Handled missing values and duplicates
	Encoded categorical variables using Label Encoding / One-Hot Encoding
	Scaled numerical features
	Removed irrelevant or highly correlated features
##Exploratory Data Analysis (EDA)
  Analyzed class imbalance between defaulters and non-defaulters
	Visualized key correlations and feature importance
	Derived insights from variables such as income, loan amount, and credit history
##Modeling
	Tested multiple algorithms: Logistic Regression, Random Forest, XGBoost, and LightGBM
	Tuned hyperparameters using cross-validation
	Evaluated models using metrics like Accuracy, F1-Score, and AUC-ROC
##Final Model
	Selected the model with the best balance between interpretability and performance
	Exported the trained model for predictions on the test dataset

