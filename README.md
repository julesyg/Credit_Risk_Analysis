# CREDIT RISK ANALYSIS

Supervised Machine Learning.

## OVERVIEW OF LOAN PREDICTION LOAN ANALYSIS:

The purpose of this analysis is to employ and evaluate six machine learning models with unbalanced classes to determine which would be best to execute credit risk analysis. 

## RESULTS:

Six machine learning models were used in this loan prediction analysis, the Balanced Accuracy Score, Precision and Recall for each model are as follows:

## Naive Random Oversampling

<img width="658" alt="Screen Shot 2023-01-04 at 8 58 41 PM" src="https://user-images.githubusercontent.com/111521163/210684378-f341185b-3005-4cc7-ae9f-566702f1e953.png"> 

- Balanced Accuracy Score: 0.6605547657197899

- Precision: high risk loans = 0.01  / low risk loans = 1.00 

- Recall: high risk loans = 0.69  / low risk loans = 0.63 

## SMOTE Oversampling

<img width="658" alt="Screen Shot 2023-01-04 at 8 59 19 PM" src="https://user-images.githubusercontent.com/111521163/210684454-4ef7f183-585b-4ad9-baa8-d32f9d7d13ef.png">

-  Balanced Accuracy Score: 0.6550858927099446

- Precision: high risk loans = 0.01  / low risk loans = 1.00 

- Recall: high risk loans = 0.63  / low risk loans = 0.68 

## Undersampling

<img width="648" alt="Screen Shot 2023-01-04 at 9 00 16 PM" src="https://user-images.githubusercontent.com/111521163/210684576-9ed5ac04-ab3f-44d6-bb57-765435aca60f.png">

- Balanced Accuracy Score: 0.5439153831192286

- Precision: high risk loans = 0.01  / low risk loans = 1.00 

- Recall: high risk loans = 0.69  / low risk loans = 0.39 

## Combination Sampling

<img width="648" alt="Screen Shot 2023-01-04 at 9 00 47 PM" src="https://user-images.githubusercontent.com/111521163/210684621-48bcd313-2705-43ce-8163-4dc9fff03da9.png">

- Balanced Accuracy Score: 0.6477226680806527

- Precision: high risk loans = 0.01  / low risk loans = 1.00 

- Recall: high risk loans = 0.72  / low risk loans = 0.57 

## Balanced Random Forest Classifier

<img width="648" alt="Screen Shot 2023-01-04 at 9 02 05 PM" src="https://user-images.githubusercontent.com/111521163/210684775-45b23762-96b4-4be5-bebc-10a7bc5fc28e.png">

- Balanced Accuracy Score: 0.7885466545953005

- Precision: high risk = 0.03  / low risk = 1.00 

- Recall: high risk = 0.70  / low risk = 0.87 

## Easy Ensemble AdaBoost Classifier

<img width="648" alt="Screen Shot 2023-01-04 at 9 02 26 PM" src="https://user-images.githubusercontent.com/111521163/210684818-c244c4fe-c999-4260-bd07-86606c46df08.png">

- Balanced Accuracy Score: 0.9316600714093861

- Precision: high risk = 0.09  / low risk = 1.00 

- Recall: high risk = 0.92  / low risk = 0.94 

## SUMMARY:

Overall, the balanced accuracy scores for all six models fell the acceptable range with values closer to 1 being better. The Easy Ensemble AdaBoost Classifier model had the best score of 0.93. The Precision of all models were all very similar. The Recall varied between models with Undersampling having the lowest results and Easy Ensemble AdaBoost Classifier the highest. 

For the credit risk analysis the Easy Ensemble Adaboost Classifier is recommended. 
