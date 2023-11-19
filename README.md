# Prediction-of-Marketing-Campaign

The objective is to develop a supervised machine learning framework to predict the success/ failure of the campaign based on customer’s response for a company. The dataset consists of marketing data from a company containing information on customer profiles, product preferences, channel performance, etc. 

The target variable is binary, with the two class labels marked as ‘0’ for ‘failure’ and ‘1’ for ‘success’ of the campaign. This is a classification problem as the target variable of the problem is discrete, i.e it is binary (0 or 1). Classification is appropriate here as the goal is to assign each instance to a specific category/ class.

The dataset is divided into two parts- training and testing. The training dataset has 2016 instances, among which 301 instances are labeled as ’1’ (indicating success), while 1715 instances are labeled as ’0’ (indicating failure). The test dataset contains 224 instances. There are 25 columns (features) in the dataset. There are also a few missing values in the dataset, mostly under the income feature. I plan to impute them using KNN imputation, and not remove them, to prevent loss of valuable information. 

I plan to begin by data visualization and preprocessing such as one-hot encoding, imputation, data scaling, etc. I will also use feature selection techniques like Information Gain, GINI Index, etc. to identify relevant features. The dataset will be trained using models such as decision tree classifiers, K- nearest neigh-
bors (KNN), random forest classifiers, logistic regression, Adaboost, Gradient Boosting, Support Vector Machine, etc, alongwith hyper parametric tuning and 5- fold validation. I will also construct a confusion matrix to find the precision, accuracy, recall, F1- measure on each of the classifiers. Based on the evaluation metrics, the best model will be used to find the labels for the test dataset.

Note: This project wass done as a part of the course- ECS308: Machine Learning.
