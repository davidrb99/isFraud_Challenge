# Practica1
### By: David Rivero Berrocoso.

## Main goal:

The main goal of this practice is to generate a model which give back the probability of some kind of fraud to happen. Additionaly, it's mandatory to analize the data, to look for profiles, to generate suitable descriptives, to select and process the variables... etc.

## Steps:

0. Dataset & Dictionary Loading


1. Problem to solve and Dataset description.

2. EDA

	2.1 Data types identification
	2.2 Duplicates columns identifications
	2.3 Target variable identification
	2.4 Missing values processing
	2.5 Identification of variables
	2.6 Outliers
	2.7 Correlations
	2.8 Variables representation
		Numerical variables representation
		Categorical variables representation

3. Objectives To Model
	3.1 Variable transformation.
	3.2 Missing values transformation
	3.3 Categorical variables encoding

4. For the target variable (Modeling).
	4.1 Splitting into Train & Test.
	4.2 Data Augmentation: Smote
	4.3 Data Scaling: MinMax Scaler
	4.4 Models
	- Linear model
	- Regression + Lasso
	- Generalized Linear Models (GLM)
	- Support Vector Machine (SVM)
	- Random Forest Classifier
	- XGBBoost Classifier
	- LightGBM
	- Other models
		* Basic Gradient Boosting Classifier
		* Decision Tree Classifier

 4.5 Best Model Selection
	* XGBBoost Classifier
	* ROC Curve
	
5. Interpretability
	5.1 Feature importance
	* Permutation Based Feature importance
	* Partial Dependence Plot
	5 Explainability

####Disclosure:
the project is going to be pressented in both HTML and .Py formats through GitHub repository. Paths are related to this directory and it can be read on any device.

#### Github:
https://github.com/davidrb99/isFraud_Challenge.git
