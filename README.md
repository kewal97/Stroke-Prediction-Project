# Stroke-Prediction-Project

A stroke is a cerebrovascular disorder that causes damage to the normal supply of blood to the brain, according to the World Health Organization (WHO). Strokes account for approximately 11% of all deaths worldwide. The condition may lead to death or long-term disability if not treated properly. The cause of strokes can be hemorrhagic or ischemic. Both hemorrhagic and ischemic strokes can occur together. Ischemic strokes are those caused by clots in the blood vessels, while hemorrhagic strokes are those caused by ruptured blood vessels. . In general, 85 percent of strokes are classified as ischemic. 

# Problem statement :

Using input parameters such as gender, age, disease status, and smoking status, determine whether a patient is likely to suffer a stroke. each row present in the data contains relevant information about the patient. Perform the necessary exploratory data analysis before building the model & estimate the accuracy of the model.

# About Dataset :

The dataset The Dataset Stroke Prediction is taken in Kaggle. have about 5110 rows of record that consists of multiple predictor variables and one of the target variable that is Outcome. Predictor variables includes the age, gender, bmi, glucose level smoking status etc.

# What the problem is :

The given Dataset is extremely inbalanced out of 5110 rows of record the stroke population is 249 while the non-stroke group has 4861 records. & we have a binary classification problem. We will make a prediction on the target variable stroke. Lastly we will build a variety of Classification models and compare the models giving the best prediction on stroke.

# Solution technologies:

We will first use panda to upload, examine and clean the dataset if needed. Then we use seaborn and matplotlib packages for exploratory analysis and visualization. Finally, Scikit_learn library will be applied with: DecisionTreeClassifier to train and predict the data to predict how many people whether get stroke or not with significant standout attributes, and the module library of confusion matrix (confusion_matrix, classification_report) to calculate the accuracy of the model.

# Analytical Approach:

To predict whether someone has a stroke or not, we need to make categorical models like a decision tree or logistic regression. The data will be split in 2 parts, 75% for training and 25% for testing purposes. With the challenge of highly imbalanced data, we decided to sample the non-stroke group to check the distribution with the original data with 95% confidence with 5% margin of error. The sample size would be 1,417 out of the population of 4,861 and the original stroke group would remain. Then we test if the non-stroke samples have similar distributions with the original data, before performing exploratory analysis between the non-stroke sample and stroke group with other attributes.

# Conclusion:
1. 3 most important variables for stroke prediction are : Age, Average Glucose Level and BMI which combined predictive power of 75%.
2. Our Logistic Regression Model have 84% probability to identify people who have stroke (from AUC score).
3. Describe AGE, BMI, glucose of stroke people.

# Contents of the repository:

Healthcare Dataset on Stroke.csv
Stroke Detection Final EDA Material.pdf
Sampling.ipynb
Modelling Draft.ipynb
DATA 5100 Project Sample Comparison.ipynb
