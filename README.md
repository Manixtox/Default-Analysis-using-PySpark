# Default-Analysis-using-PySpark
Analysis and prediction of default loans using PySpark, with a dataset extracted from Kaggle .
1.	PROBLEM

Analysis and prediction of default loans using PySpark, with a dataset extracted from Kaggle .

A.	data set (Default_Fin.csv  )

i.	Dimensions:
•	10000 records.
•	Index, mark of employee or unemployed, bank balance, client salary, mark of delinquency or no delinquency.

ii.	Format: csv

iii.	Metadata : Contains a set of real data (loans or credits) from a financial institution.

•	Index : identifier number
•	Employed : Boolean flag, where:
1 = employee
0 = unemployed.
•	Bank balance: Customer's bank balance.
•	annual salary : Annual salary of the client.
•	Defaulted : boolean flag, where:
1 = in arrears
0 = no default


2.	GENERAL SOLUTION

Dataset link
https://www.kaggle.com/code/ellaphamvn/loan-default-prediction-recall-99-accuracy-69/data

Below is a summary of the sequence of steps and tasks carried out during the project attention process.

•	Pyspark image via docker .
•	Pyspark jupiter notebook session on our computer, it is required to import the dataset Default_Fin.csv.
These data will allow the analysis of credits in deafault, for this the dataset is replicated to a new dataframe prest2 .


•	data frame is analyzed prest2 , under this filters:

-	Account balances greater than $100,000.
-	Count balances greater than $100,000.
-	Count the cases that are in default and those that are not, where it is evident that the data is unbalanced.
-	We count the number of clients with employment.
-	The average annual income is obtained, the existence of isolated data that the average tends to rise is infered.
-	The number of unemployed people who are in default is identified.

