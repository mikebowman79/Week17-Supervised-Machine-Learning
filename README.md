# Week17-Supervised-Machine-Learning: Credit Risk Analysis

Overview: The purpose of this challenge is to employ supervised machine learning models to assess credit risk. Models that were used include the following:
•	NAÏVE Random Oversampling
•	SMOTE Oversampling
•	Undersampling 
•	Combination Sampling
•	Balanced Forest Random Classifier
•	Easy Ensemble Classifier

Results:
NAÏVE Random Oversampling
•	Balanced accuracy score is 0.649
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .62 for high-risk loans and .68 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045708-24170ba2-cc2c-4e8c-a211-8b02b27adb60.png)

SMOTE Oversampling
•	Balanced accuracy score is 0.64455
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .63 for high-risk loans and .66 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045726-f2a93702-13a3-4a7f-bda6-fc330ab965ec.png)
Undersampling 
•	Balanced accuracy score is 0.64437
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .60 for high-risk loans and .43 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045741-6e55a582-737d-4432-9899-72b8a42b2c37.png)
Combination Sampling
•	Balanced accuracy score is 0.51581
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .70 for high-risk loans and .57 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045761-0a836b1e-f092-4523-9e2c-54ab972cc53f.png)
Balanced Forest Random Classifier
•	Balanced accuracy score is 0.7885466545953005
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .70 for high-risk loans and .87 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045785-21dd60da-b233-491d-8da4-c2794feb6928.png)
Easy Ensemble Classifier
•	Balanced accuracy score is 0.93166
•	Precision is low for High-risk loans
•	Precision is high for Low-risk loans
•	Recall is .92 for high-risk loans and .94 for low-risk loans
![image](https://user-images.githubusercontent.com/101996041/182045802-9bb39980-4e29-48ce-9f20-aa171a1a9601.png)

Summary

Of the models tested the Easy Ensemble Classifier was the most accurate at 93% and the only model over 80%. This model also had the highest recall scores for both high-risk and low-risk loans. 




