# Predict-Loan-Eligibility-for-Dream-Housing-Finance-company
Author - Dnyanesh Walwadkar
d.walwadkar@se21.qmul.ac.uk
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.  Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.


![alt text](https://github.com/dnyanshwalwadkar/Predict-Loan-Eligibility-for-Dream-Housing-Finance-company/blob/main/Correlation.PNG)

Hypothesis - 
* Applicants with high income should have more chances of loan approval.
* Applicants who have repaid their previous debts should have higher chances of loan approval.
* Loan approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.
* Lesser the amount to be paid monthly to repay the loan, higher the chances of loan approval.
* Lets try to test the above mentioned hypotheses using bivariate analysis

To check how robust our model is to unseen data, we can use Validation. It is a technique which
involves reserving a particular sample of a dataset on which you do not train the model. Later,
you test your model on this sample before finalizing it. Some of the common methods for
validation are listed below:
• The validation set approach
• k-fold cross validation
• Leave one out cross validation (LOOCV)
• Stratified k-fold cross validation
If you wish to know more about validation techniques, then please refer this article:
https://www.analyticsvidhya.com/blog/2018/05/improve-model-performance-cross-validation=
in-python-r/
 Let us understand how K-fold cross validation
works:
*  Stratification is the process of rearranging the data so as to ensure that each fold is a good
representative of the whole.
For example, in a binary classification problem where each class comprises of 50% of the
data, it is best to arrange the data such that in every fold, each class comprises of about
half the instances.
* It is generally a better approach when dealing with both bias and variance.
* A randomly selected fold might not adequately represent the minor class, particularly in
cases where there is a huge class imbalance.
Below is the visualization of a stratified k-fold validation when k=5.

![alt text](https://github.com/dnyanshwalwadkar/Predict-Loan-Eligibility-for-Dream-Housing-Finance-company/blob/main/12.PNG)
