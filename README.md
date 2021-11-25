# Digits_Classifier
Comparison of MNIST handwritten digits classsifiers including ANN, CNN and SVM

## Procedure
* Importing the neccessary libraries
* Importing the MNIST handwritten digits dataset using the keras library
* Scaling and flattening the data to improve accuracy and ensure to prevent errors as some models mandate the use of single column arrays as inputs
* Hyperparameter tuning of SVM using GridSearchCV
* SVM model fitting and determination of accuracy
* KNN model fitting and determination of accuracy
* ANN model without hidden layer creation, training and measurement of accuracy
* ANN model with hidden layer creation, training and measurement of accuracy
* Reshaping the dataset
* CNN model creation, training and measurement of accuracy
* Using confusion matrix to find where the model predicted incorrectly
* Comparing SVM, KNN, GaussianNB, Linear Discriminant Analysis and Decision Tree Classifier using GridSearchCV
* Comparing the accuracy of SVM with ANN and CNN models
* Arriving at the conclusion that SVM is the best classifier