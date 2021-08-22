# Credit_Risk_Analysis

## Overview of the analysis

In this project,  I am using imbalanced-learn and scikit-learn libraries to build machine-learning models to predict credit risk using the credit card credit dataset from LendingClub.
I used for oversampling the data the RandomOverSampler and SMOTE algorithms, and for the undersampling I used the ClusterCentroids algorithm. And also for the other models I used a combination approach to over and undersample the data using smoteenn. 
Finally I used two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using these algorithms, I have been able to resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Results

- <h5>Naive Random Oversampling</h5> <ul><li>The balanced accuracy score : 65.44%</li><li>The precision : 1%</li><li>The recall :  69%</li></ul>
<img width="1382" alt="naive" src="https://user-images.githubusercontent.com/61424555/129748193-b970eead-07e2-4c34-9ffb-8b886de6e3a9.png">


- <h5>SMOTE oversampling</h5> <ul><li>The balanced accuracy score : 66.28%</li><li>The precision : 1%</li><li>The recall :  63%</li></ul>
<img width="1286" alt="smote" src="https://user-images.githubusercontent.com/61424555/129749311-42fe076b-d186-46b5-8ca9-4601e3810c01.png">


- <h5>Undersampling</h5> <ul><li>The balanced accuracy score : 54.47%</li><li>The precision : 1%</li><li>The recall :  69%</li></ul>
<img width="1315" alt="undersampling" src="https://user-images.githubusercontent.com/61424555/129749736-4cfb9e89-afdb-454b-b62a-22536ec34f95.png">


  - <h5>Combination(over and undersampling)</h5> <ul><li>The balanced accuracy score : 64.76%</li><li>The precision : 1%</li><li>The recall :  71%</li></ul>
<img width="1355" alt="combination" src="https://user-images.githubusercontent.com/61424555/129750269-c528db6b-a1bb-422c-978f-e3faf0d53c14.png">


  - <h5>Balanced Random Forest Classifier</h5> <ul><li>The balanced accuracy score : 76.06%</li><li>The precision : 3%</li><li>The recall :  64%</li></ul>
<img width="1293" alt="random forest" src="https://user-images.githubusercontent.com/61424555/129750666-b350d93e-d15a-4254-884e-4a21840c067c.png">


  - <h5>Easy Ensemble AdaBoost Classifier</h5> <ul><li>The balanced accuracy score : 91.78%</li><li>The precision : 9%</li><li>The recall :  89%</li></ul>
<img width="1353" alt="ensemble" src="https://user-images.githubusercontent.com/61424555/129750953-ecf210de-8e70-4e6e-8f13-0e4889841135.png">
  


## Summary 

The goal of this project was to determine which model is best at predicting which loans are the highest risk. After the model training anad analyzing the results we can Conclude that the ensemble classifiers have the highest accuracy score along with the recall compared to the other models, also It appears that the Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.
