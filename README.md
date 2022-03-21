# Credit_Risk_Analysis
Module 17 Challenge



Overview of the loan prediction risk analysis:

- The purpose of this analysis is to predict the credit risk by using the Loan status column which give us either "low risk" and "high risk".  We then create 6 different outcome of machine learning using the following RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier. 



- Results:

  - There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models **(15 pt)**

    

  - **RandomOverSampler** -  balance accuracy score is **65%**. Precision of 0.01 high risk and 1.00 for low risk. Under recall, 74% high risk and 55% low risk.![Naive](https://user-images.githubusercontent.com/94090097/159194346-43c7f566-f1df-4b2b-b01f-9bec54fecd27.png)

  - **SMOTE** - balance accuracy score is **66%**. Precision of 0.01 high risk and 1.00 for low risk. Under recall, 73% high risk and 69% low risk.![Smote](https://user-images.githubusercontent.com/94090097/159194353-f9b007c9-f7ad-442a-a916-ff1b2ad9a789.png)

  - **ClusterCentroids** - balance accuracy score is **54%**. Precision of 0.01 high risk and 1.00 for low risk. Under recall, 67% high risk and 42% low risk.

    

  - ![Under](https://user-images.githubusercontent.com/94090097/159194368-1fe01dfc-e7d7-449e-b300-c3b7eec74faf.png)

  - **SMOTEENN** - balance accuracy score is **64%**. Precision of 0.01 high risk and 1.00 for low risk. Under recall, 70% high risk and 58% low risk.

  - ![Com](https://user-images.githubusercontent.com/94090097/159194373-64645a38-3a0d-4994-986d-3ef2a3c37ac9.png)

  - **BalancedRandomForestClassifier** - balance accuracy score is **79%**. Precision of 0.03 high risk and 1.00 for low risk. Under recall, 70% high risk and 87% low risk.![Balance](https://user-images.githubusercontent.com/94090097/159194379-a225ec45-210a-4d51-802d-af1d90982800.png)

  - **EasyEnsembleClassifier** - balance accuracy score is **93%**. Precision of 0.09 high risk and 1.00 for low risk. Under recall, 92% high risk and 94% low risk.![Ensemble](https://user-images.githubusercontent.com/94090097/159194383-64f1418c-ffc7-460e-8cd0-15c27f166a50.png)

- **Summary:**
  - There is a summary of the results **(2 pt)** 
  - Using 6 different machine learning the outcome for each individual model were different. Using both Balance Random and Easy Ensemble Classifier shows the high output on both respective recall of high and low risk. While using Random OverSampler, SMOTE and SMOTEENN the recall output for high and low risk were in range of 55 - 75%. On the other hand, the Cluster Centroids were 42% low risk and 67% high risk.
  - There is a recommendation on which model to use, or there is no recommendation with a justification **(3 pt)**
  - No recommendation to use one of the 6 model due to the fact that the high and low risk recall output are fairly close to each other. 

