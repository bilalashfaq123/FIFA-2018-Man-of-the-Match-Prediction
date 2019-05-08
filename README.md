# FIFA-2018-Man-of-the-Match-Prediction
This is the Data Science Machine Leaning Project. Data is provided by kaggle, and the goal is to Predict the Man of the Match from the given data set.
# Steps
## 1. Data Cleaning
In this step, missing values and outliers are handled, as the rows "Own Goals, Own goal Time, and 1st goal" have most missing values, instead, they have 90% of the missing values, so neglecting them is a good idea.
## 2. Data Visualization
In order to obtain any trend from the data for a best model, Exploratory Data Analysis (EDA) is applied, and correlation is found for checking the dependencies of different features on the labels. 
## 3. Data Processing And Performance Evaluation
Three (3) models are applied on the Data.
1. Random Forest
2. Decision Tree
3. Naive Bayes.
### 1. Random Forest
Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes or mean prediction of the individual trees
Random Forest gave an accuracy measure of 79%, which is the highest among all.
### 2. Decision Tree
A decision tree is a simple representation for classifying examples. Decision tree learning is one of the most successful techniques for supervised classification learning.
Decision tree provided a good set of results like about 61% of the accuracy for the training data and around 80% of the accuracy for testing data. Although it is under fitted model, but gives us a decent accuracy.
### 3. Naive Bayes
It is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature
Naïve Bayes does not provide as good accuracy as other provided in the given data set. It’s actually 50% which is random guessing and 87% accuracy for the testing data 
# Cross Validation
Cross Validation for all the models have also been done. you can see the results in my comitted kaggle kernel,
# Data File
Data file is also provided in the repository named "FIFA 2018 Statistics"

# For Support and Help
Email: bilal75210@gmail.com
kaggle link: https://www.kaggle.com/bilal75210/project-data-science
