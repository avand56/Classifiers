# Classifiers
This repository contains all the classifiers i have completed or am currently working on.

# Credit card fraud classifier
For this classifier, logistic regression was used to identify a positive case of credit card fraud from a negative case. 
The data had PCA applied before it was imported into the workbook.
First, a classifier trying to determine fraud using only the amount was used to try to classify as positive case of fraud. The performance was poor, so the rest of the PCA transformed data was used along with the purchase amount was used to classify fraudulent transactions. This model performed much better, with an AUROC of 0.91 vs ~0.50 for thr amount only classifier. This shows the classifier did a good job at predicting fraudulent transactions.
The sensitivity, recall, and accuracy are all calculated to assess the performance of the classifier.

#
I am currently working on another random forest classifier for practice.
