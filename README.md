# Credit_Risk_Analysis


# Overview of the analysis:

The overview of this Analysis is to predict  credit risk , We oversample the data using the RandomOverSampler and SMOTE algorithms.We did also
Undersample the data using the ClusterCentroids algorithm. in addition we  Used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm,
Comparing  two machine learning models that reduce bias,  such as BalancedRandomForestClassifier and EasyEnsembleClassifier.


We  evaluate the performance of these models and make a recommendation on whether these information legit  to predict credit risk ,comparing two machine learning models minimize  bias



# Results


![Ada](https://user-images.githubusercontent.com/82621077/130371140-ef9746e0-47e0-4e4e-9422-21086e378a11.png)


# 1- Easy Ensemble AdaBoost Classifier results: the accuracy score is 91.7% the precision is 99% and the recall is 94%





![balan](https://user-images.githubusercontent.com/82621077/130371418-b5d6e339-1f1f-4aab-9a4f-16393faf5da3.png)

# 2- Balanced Random Forest Classifier results: the accuracy score is 77.2% the precision is 99% and the recall is 87%







![Combination](https://user-images.githubusercontent.com/82621077/130371539-cbf355ad-c5cc-4b61-9777-e1bccbf7eb16.png)

# 3. Combination(over and undersampling) results: balanced accuracy score is 53% the precision is 99% and the recall is 68% overall





![Un](https://user-images.githubusercontent.com/82621077/130371614-e62d14db-5257-4b7c-b49e-fd6aa48df7ae.png)

# 4- Undersampling results: balanced accuracy score is 43 % overall, the precision is at 99% and the recall is 44%






![smote](https://user-images.githubusercontent.com/82621077/130371704-a5df3777-03b9-4c76-8ddf-98726d1e37f2.png)


# 5- SMOTE oversampling results: the accuracy score is 66.6%, the precision for the high_risk loans has a low positvity again at 1% and recall is 67% overall








![Naive](https://user-images.githubusercontent.com/82621077/130371761-12a3b2cf-b9c1-4979-8c54-8a6dc36dd6a6.png)


# 6-Naive Random Oversampling results: Our balanced accuracy test it 68%, the precision for the high_risk has a very low positivity at 1% and the recall is 68%




# Summary 

This credit risk Analysis  shows weak precision in determining  that credit risk is high 
The Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
The EasyEnsembleClassifier model shows a recall of 91.7% so it detects almost all high risk credit.  with a low precision, 
For those reasons I would not recommend the bank to use any of these models to predict credit risk.
In this anaylsis we can not rely on outcomes a lot of low risk credits are still falsely detected as high risk


