# Credit-Score-Evaluation

This project looks at how banks and other Financial Institutions decide on who deserves to be given a loan and most importantly , how much of a loan one deserves. This is an ongoing Machine learning Project under the umberella of binary classification applying well known logistic algarithms . A decison tree regressor algarithm is employed in this instance given its ability to handle both both regression and classification tasks . 

## Some of the most important  Features provided in this Project selected based on the pearson Pearson correlation coefficient > 0.3 . 

- **Num_Bank_Accounts** :This describes how many bank accounts one has .
- **Num_Credit_Card**: This describes the Number of credit Cards a prospect loan beneficery has .
- **Interest_Rate** :Research has shown that clients with a relatively higher interest rate are most likely going to struggle with paying back a specific loan .
- **Num_of_Loan** :Existing loans massively play a huge role given one is most likely to use a new loan to pay back an old loan , in such as case, we expect a relatively very low credit score .
- **Delay_from_due_date** Delay of a minimum payment means a client is most likely to have negative effect on h/her credit score . This is because a longer delay often leads to late payment charges which often increase with longer delays .
- **Num_of_Delayed_Payment**: Number of Delayed payments is counted as the frequencies one has failed to make a payment on time . One failing to make ontime minimum payments on time is most likely to delay in the future , for that matter, this leads to a low credit score
- **Outstanding_Debt** : An outstanding Debt represents the amount of money owed by a credit card or loan , Having a high outstanding balance relative to ones credit card limit has a negative effect on ones credit score .
- **Num_Credit_Inquiries** :Inquries are in two forms , soft and hard . Hard inquiries often times negatively impact your credit score and remain on your credit report for up to two years.
- **Credit_History_Age** : This refers to how long one has been using credit . The longer an account has been open and active , the better it is for ones credit score . A longer credit card history contributes positively to ones credit score .
- **credit_mix** : This refers to the various types of loan accounts that make up your credit report such as installment loans like credit cards, student loans, automobile loans, and mortgages .Having a broader credit mix, gibes creditors more information about your ability to manage different types of credit.

  ## Data Sources
  This project utilizes data from a public domain which can be easily accessed online .

  ## Requirements / Prerequisites
  Before running this script, ensure you have the following installed:
  - Python 3.x
  
  You can install the necessary Python libraries using pip:
  ```bash
  pip install Numpy
  pip install pandas
  pip install jupyter notebook 
  pip install numpy scipy scikit-learn
  pip install linear_model
