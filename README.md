# Binary Classification 

A binary classification model using 2 different machine learning methods 
Logistic Regression and Random Forest 
.
Logistic Regression uses a sigmoid function that keeps the predictions of the model within the range of 0 and 1

![alt text](https://cdn-images-1.medium.com/max/1600/1*zfH9946AssCx4vzjaizWeg.png)

There are 3 types of logistic regression 
Binary Logistic Regression, Multinomial Logistic Regression, Ordinal Logistic Regression

I used Binary Logistic Regression since there were only two values that needed to be predicted as either a 1 or a 0 

Random Forests consist of  multiple desicions trees that can be averaged
I used a Random Forest Regression Model.

![alt text](https://cdn-images-1.medium.com/max/1600/1*i0o8mjFfCn-uD79-F1Cqkw.png)

The model has over fitted both models especially the random forest classifier.
THE REASONS FOR this is the homogeneous target value of 0, 
since there is no variaty in the target the model fits too well and will face problem when it is presented different values.

In this demonstration I have used logistic regression for binary classification(utilizing scikitlearn) and a RandomForestClassifier, to access the performance of the methods, confusion_matrix method from sklearn.metrics was used 
The confusion matrix illustrates an array presenting the correct positives and negatives on the top and false positive and negatives on the bottom.

the pros and cons of the algorithms 
The pros and cons of logistic regression 
 pros: +works well with binary classification +low variance
 cons: -there is a high bias - the model is likely to perform poorly if exposed to new and different values 
 he pros and cons of Random Forest Classifier 
 pros: + good for multiple features like in this example
 cons: - when the target value has no diversity, overfitting is prominent
 Pros and cons of ANN for binary classification
 pros: + better predictions
 cons: - takes a long time to train with big datasets

Please note the dataset isn't provided in the repo becsause the rights of it was owned by a third party. This is a work in progress
