A large number of problems in data mining are related to fraud detection. Fraud is a common problem in
auto insurance claims, health insurance claims, credit card transactions, financial transaction and so on.
The data in this particular case comes from an actual auto insurance company. Each record represents an
insurance claim. The last column in the table tells you whether the claim was fraudulent or not. 


This project focuses on detecting fraudulent transactions using various machine learning techniques. It demonstrates a step-by-step approach for building, tuning, and evaluating classification models for fraud detection, highlighting the following key components:

	Exploratory Data Analysis (EDA) & Pre-Processing: Initial data exploration and preprocessing steps to clean and transform the dataset for model training.

	Basic Decision Tree Model: A simple decision tree classifier is implemented and evaluated on the dataset to serve as a baseline model.
	Random Search for Decision Tree: Hyperparameter tuning is performed using RandomizedSearchCV to find the optimal parameters for the decision tree model.
	
 	Grid Search for Decision Tree: A more exhaustive search using GridSearchCV is carried out to fine-tune the decision tree's performance further.
