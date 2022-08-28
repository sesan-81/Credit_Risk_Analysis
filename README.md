# Credit_Risk_Analysis



1.	OVERVIEW OF THE LOAN PREDICTION RISK ANALYSIS



Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:


a.	imbalanced-learn

b.	scikit-learn

c.	RandomOverSampler

d.	SMOTE algorithms

e.	ClusterCentroids algorithm

f.	SMOTEENN algorithm

g.	BalancedRandomForestClassifier (bias reduction model)

h.	EasyEnsembleClassifier (bias reduction model)

•	THE PURPOSE OF THIS ANALYSIS 

a.	Explain how a machine learning algorithm is used in data analytics.

b.	Create training and test groups from a given data set.

c.	Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.

d.	Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.

e.	Compare the advantages and disadvantages of each supervised learning algorithm.

f.	Determine which supervised learning algorithm is best used for a given data set or scenario.

g.	Use ensemble and resampling techniques to improve model performance.








2.   RESULTS


The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:






I.	NAIVE RANDOM OVERSAMPLING


![image](https://user-images.githubusercontent.com/104377031/187078974-1083cd56-c265-421c-a967-bfbc1cf1fd09.png)


 
a.	Balanced Accuracy:      0.6413263312262552

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.60/0.68













II.	SMOTE OVERSAMPLING

 
 
 ![image](https://user-images.githubusercontent.com/104377031/187078993-f4f5b4e3-0506-4018-8507-1acf6822c17a.png)


a.	Balanced Accuracy: 0.6374415316001305

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.60/0.68












III.	UNDERSAMPLING

 
 ![image](https://user-images.githubusercontent.com/104377031/187079454-73ecc902-9f5f-49c2-bbc2-d53d98c28cd9.png)



 
 

a.	Balanced Accuracy: 0.6393350818456878

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.70/0.58











IV.	COMBINATION UNDER-OVER SAMPLING


![image](https://user-images.githubusercontent.com/104377031/187079301-826eec6f-649e-4de4-adc3-f33843ed2632.png)


 

a.	Balanced Accuracy: 0.6393350818456878

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.70/0.58











V.	BALANCED RANDOM FOREST CLASSIFIER


![image](https://user-images.githubusercontent.com/104377031/187079268-8a653185-2251-4f57-8572-7daa5deeb142.png)


 

a.	Balanced Accuracy: 0.7885466545953005

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.70/0.87











VI.	EASY ENSEMBLE ADABOOST CLASSIFIER


![image](https://user-images.githubusercontent.com/104377031/187079218-208bb90d-45a6-4bbf-8d7b-4957c90a3d9d.png)


 

a.	Balanced Accuracy: 0.9316600714093861

b.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

c.	Recall: High/Low risk = 0.94/0.92


3.	SUMMARY

•	Going through all the six model, the Easy Ensemble AdaBoost Classifier model had the highest overall accuracy of approximately 93 percent and a precision rate of 9 percent, while predicting High Risk Candidate. 

The recall was also had the highest at 92 percent high risk and 94 low risk percent as compared to the other models, the f1 score had 16percent for high risk and 97 precent for low risk.

                     •	RECOMMENDATION

I therefore recommend the Easy Ensemble AdaBoost Classifier model based on the analysis in the summary section.

