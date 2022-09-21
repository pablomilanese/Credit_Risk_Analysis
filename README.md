# CREDIT RISK ANALYSIS

## OVERVIEW

The purpose of this project was to evaluate a credit card dataset using statistical reasoning and machine learning to predict credit risk.


## RESULTS

**RandomOverSampler Model**<br>

Balance Accuracy Score 78%

<img width="393" alt="image" src="https://user-images.githubusercontent.com/105120795/191426083-6cf24a52-32fa-47f9-9bad-dfda4f2f20b0.png">

<img width="378" alt="image" src="https://user-images.githubusercontent.com/105120795/191426107-eba2ab52-142a-401b-a275-d0992a9cf009.png">


**SMOTE Model**

Balance Accuracy Score 64%

<img width="395" alt="image" src="https://user-images.githubusercontent.com/105120795/191426689-e16b36fa-a689-4e2f-b41c-0eb8b7e41b81.png">

<img width="417" alt="image" src="https://user-images.githubusercontent.com/105120795/191426717-e61229ee-7d18-47d1-82ab-90a016b11966.png">

**Undersampling**

Balance Accuracy Score 54%

<img width="386" alt="image" src="https://user-images.githubusercontent.com/105120795/191426981-a19c3bad-2120-4185-8097-c9d64a987ff0.png">

<img width="389" alt="image" src="https://user-images.githubusercontent.com/105120795/191427024-f7c6a4c0-b993-41fc-ab2e-d6678b9c8128.png">

**SMOTEENN**

Balance Accuracy Score 61%

<img width="423" alt="image" src="https://user-images.githubusercontent.com/105120795/191427487-98254fed-88b3-4f14-9133-80373d4052dd.png">

**BalancedRandomForestClassifier Model**

Balance Accuracy Score 78%

<img width="400" alt="image" src="https://user-images.githubusercontent.com/105120795/191428767-0531de6f-5585-42dd-af67-b7092fbbf821.png">

<img width="423" alt="image" src="https://user-images.githubusercontent.com/105120795/191428791-21b228ea-a7ea-4dd7-90d5-b25f9abfbc2a.png">

**EasyEnsembleClassifier Model**

Balance Accuracy Score 92%

<img width="407" alt="image" src="https://user-images.githubusercontent.com/105120795/191428869-317b9880-5a42-470a-be22-66b10357ebcd.png">

<img width="419" alt="image" src="https://user-images.githubusercontent.com/105120795/191428893-3f74d234-6d21-4d5f-80e2-7b71f5d8d76c.png">


## SUMMARY

After comparing the different models it is clear that the best option is EasyEnsembleClassifier. It presented a Accuracy Score of 92%, as well as the highest recall score.
