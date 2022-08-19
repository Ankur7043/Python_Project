# Prediction of loan eligibility using machine learing
# Aim
To predict wether person eligible  for loan or not
# objective
To check whether the person can get the loan or not by evaluating the data with the help of decision tree classifiers which can gives the accurate result for the prediction.
# Methodology
**Data Collection:-** We worked on Secondary Data, Secondary data collected  from kaggel.

**Data infromation**

| Variable | Description |
| --- | --- |
| Loan_ID | Unique Loan ID|
| Gender | Male/ Female |
| Married | Applicant married (Y/N)|
| Dependents |	Number of dependents |
| Education	| Applicant Education (Graduate/ Under Graduate)|
| Self_Employed |	Self employed (Y/N) |
| ApplicantIncome |	Applicant income |
| CoapplicantIncome |	Coapplicant income |
| LoanAmount |	Loan amount in thousands |
| Loan_Amount_Term |	Term of loan in months |
| Credit_History |	credit history meets guidelines |
| Property_Area |	Urban/ Semi Urban/ Rural |
| Loan_Status |	Loan approved (Y/N) |

**Kaggle link** https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset?select=test_Y3wMUE5_7gLdaTN.csv

**Data CLeaning:-** Data cleaning is the process of preventing and correcting these errors.The dataset consists of many null values which will affect the accuracy of the model during prediction. If numeric  data have null value then replace with mean  and if  categorical data have null value then replace with mode.

**Exploratory Data Analysis:** In exploratory Data Analysis we are explor data and find the relation between variables and  also visualize graph .

**Algorithms:-** We use machine learning algorithm.

1 Classification 

2 Logistic Regression

3 Decision Tree

4 Random Forest

5 KNeighborsClassifier

**Evaluation:-** After model development we check the accuracy for   accurate results.
# Tools and Technologies
1 Python3

2 Machine Learning

3 Jupyter notebook

4 numpy

5 pandas

6 seaborn

7 matplotlib

8 Sk-Learn

# Conclusion

 1 We have developed a model which can easily predict that the person will get loan or not.
 
 2 Machine learning has helped a lot in developing this model which gives precise results
 The accuracy of Gaussian Naive Bayes is 82.16 % and for Decision Tree it is 82.1% accuracy.
