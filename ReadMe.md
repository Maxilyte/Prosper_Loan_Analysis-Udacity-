# Factors That Affects The Success of A Loan Application


## Dataset Overview

The dataset contains 113,937 loans with 81 features which includes but not limited to the following; LoanOriginalAmount, BorrowerAPR, StatedMonthlyIncome, Term, ProsperRating (Alpha), EmploymentStatus and many others.it also has more than 50% of the columns containing numerical data. 871 data points were removed due to inconssitency and non relevance to the main focus of my investigations.The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), 
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)



## Summary of Findings


>This Prosper loan data explorations was aimed at the motivations accross different borrowers when applying for loan, and also the different factors that maay affect the Success of a Loan application.

>In terms of borrower motivations, we found surprising results. Rather than take loans to start businesses or purchase assets, the largest population seems to take large amount of Loans t finance weddings, child adoptions, boat acquisitions, and the purchase of engagement rings; THis are things that oridinarily doesnt have any return on investment, hence money spent on them can not be recovered. This explains the reason, we have Many people taking Loans just to finance their debts. Debt consolidation also accounts for the highest loan amounts collected from the platform on average. While all these may point to possibly self indulgent reasons, it can also be the liefstyle of the people living in that Region

>We also measured loan favorability using the annual percentage rate attached to a loan (the Borrower APR). we found out that the sucess of most Loan application is influenced positively by high and verifiable incomes, homeownership, low debt to income ratio, and the presence of a current means of employmenWe ,Also Borrower APR is negatively correlated with the loan original amount, loan term, and prosper rating( these are only detailed informations needed while filling out an application form not an asset that might  be considered as collateral).

>On further exploration, another surprising interaction was discovered. There seemed to be a dichotomy in the interaction between borrower APR and prosper ratings. Between the lower ratings of HR to B, borrower APR and prosper ratings were negatively correlated. This interaction turns positive within the high prosper rating group (B to AA). We attributed this to the possible influence of lurking variables, such as the loan term, and borrowing power of high income earners who are usually rated higher on the prosper scale. High income earners seemed to borrow more when long-term loans are involved, increasing their debt to income ratio. Hence, an increase in APR might be a great way to disincentivize 'overborrowing'. On the other hand, decreasing APR by term might be a great way to encourage low-rated borrowers to take long-term loans; giving them enough time to repay their loan.  


## Key Insights for   The Presentation

>For the presentation, I  focus on features that could motivate borrowers to take up loans. Some the vairable i used includes the borrower APR, Original loan amount, Prosper rating. Employment Status I started by showing the distribution of borrower APR and loan amount variable. Then, I showed the relationship between APR vs. loan amount, as well as APR vs. rating. I also investigated the effect of rating on ralationship between APR and loan amount, as well as the effect of rating on relationship between borrower APR and term.



```python

```
