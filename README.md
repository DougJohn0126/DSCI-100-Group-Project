# Can we use the health report information to predict whether a patient has heart disease?
by Alan Cho, Bowen Cui, Jia Yi, Kiki

This project was done in December 2022 as a entry level data science course at UBC.

The study aimed to create a validation set to determine the number of k-nearest-neighbors that yield the most accurate predictions and perform a 5-fold cross validation on the training data. From there a model was built using the best K value and used to predict on the test dataset patients that are likely to have heart disease and those who are not.

Dataset from: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Future considerations: 
Even though there are a few numerical predictors in our data set, we only used the two that we thoght are the most significant. Testing several predictors to determine which one has the most influence could have potentially expanded the study.  A 3D model could be created by simultaneously using three predictors. However, given our group's existing capabilities, this would have been challenging to implement. Addionally KNN performance is limited for a large number of classifiers. Therefore for classifying different degrees of heart disease/ tying to identify more than 2 types, the current methodology may not scale well.
