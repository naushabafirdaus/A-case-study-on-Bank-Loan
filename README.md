# A-case-study-on-Bank-Loan

A finance company that specializes in lending various types of loans to urban customers, faces a challenge that some customers who don't have a sufficient credit history take advantage of this and default on their loans. My task as a data analyst at a finance company is to use Exploratory Data Analysis (EDA) to analyze patterns in the data and ensure that capable applicants are not rejected.
When a customer applies for a loan, any financial company faces two risks:
i.e
If the applicant can repay the loan but is not approved, the company loses business.
If the applicant cannot repay the loan and is approved, the company faces a financial loss.
The dataset I'll be working with contains information about loan applications. It includes two types of scenarios:

Customers with payment difficulties: These are customers who had a late payment of more than X days on at least one of the first Y installments of the loan.
All other cases: These are cases where the payment was made on time.

When a customer applies for a loan, there are four possible outcomes:-
Approved: The company has approved the loan application.
Cancelled: The customer cancelled the application during the approval process.
Refused: The company rejected the loan.
Unused Offer: The loan was approved but the customer did not use it.

My goal in this project is to use EDA to understand how customer attributes and loan attributes influence the likelihood of default.

Business Objectives:
The main aim of this project is to identify patterns that indicate if a customer will have difficulty paying their installments. This information can be used to make decisions such as denying the loan, reducing the amount of loan, or lending at a higher interest rate to risky applicants. The company wants to understand the key factors behind loan default so it can make better decisions about loan approval.

Data Analytics Tasks:

A. Identify Missing Data and Deal with it Appropriately: 
It is essential to handle missing data effectively to ensure the accuracy of the analysis.

B. Identify Outliers in the Dataset: 
Outliers can significantly impact the analysis and distort the results. So, we need to identify outliers in the loan application dataset.

C. Analyze Data Imbalance: 
Data imbalance can affect the accuracy of the analysis, especially for binary classification problems. Understanding the data distribution is crucial for building reliable models.

D. Perform Univariate, Segmented Univariate, and Bivariate Analysis: 
To gain insights into the driving factors of loan default, it is important to conduct various analyses on consumer and loan attributes.

E. Identify Top Correlations for Different Scenarios: 
Understanding the correlation between variables and the target variable can provide insights into strong indicators of loan default.
