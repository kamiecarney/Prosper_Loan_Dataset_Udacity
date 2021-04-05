# Effects of Attributes of Loan Applicants
## by Kamie Carney


## Dataset

> The Prosper loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate, current loan status, borrower income, and others.  While wrangling the data, I removed columns that were not necessary for my analysis in order to make the dataset more succinct.  I also changed data types to datetime or categorical as required and made the variables IncomeRange, EmploymentStatus, and LoanStatus ordered categorical data types.


## Summary of Findings

> The income range category shows a relationship with a higher borrower interest rate in the "Not employed" or "1-24,999" categories. Not too surprising. Similarly unemployed individuals also show a higher loan interest rate. The mean interest rate for loan types was the highest for cosmetic procedures, followed by household expenses. Debt consolidation and baby adoption seem to account for the highest loan amounts and the more money people made, the higher the loan appears to be. 

> When I ran a heat map with the correlations of the numeric variables, I was surprised to see that none had a strong relationship. The strongest correlation was a negative relationship between borrower interest rates and credit score. While I did expect there to be a relationship between the two variables, it was unexpectedly small.

> However, when I ran the borrower interest rates against the categorical variables, the income range categories of "Not employed" or "1-24,999" shows a relationship with a higher borrower interest rate which was what was expected. Similarly unemployed individuals also show a higher loan interest rate. The mean interest rate for loan types was the highest for cosmetic procedures, followed by household expenses.

> It was interesting to observe that the average loan amount for the defaulted or overdue dataframe was less than the dataframe as a whole but the interest rate for those loans was higher by .04.

> The factors that most seemed to affect a loan's outcome was the amount of money borrowed and the interest rate of the loan. Higher interest, high value loans seems to be more likely to be past due. Employed individuals had the highest spread in the data, which makes sense since I assume employed individuals are more likely to apply for and receive loans.

> As the borrower's credit score increases, the interest rate decreases. There are a couple of instances where you can also see some affect of loan amount on the interest rate as well but it's not as dramatic.


## Key Insights for Presentation

> The factors that most seemed to affect a loan's outcome was the amount of money borrowed and the interest rate of the loan. Higher interest, high value loans seems to be more likely to be past due. 

> The factors that most affected the borrower's interest rate were narrowed down by the correlation heat matrix. None of the features had a strong correlation but the highest was the credit score. As the borrower's credit score increases, the interest rate decreases.