# Loan data exploration 


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
> 
> I replaced the 'other' value from EmploymentStatus column with NaN values and didn't include it in my invisitigation because it provided no information.


## Summary of Findings

> The distribution of Borrower rates looks roughly normal but with an isolated peak at nearly 0.32. The bulk of the interest rate is between 0.12 and 0.2 and the bulk other than the peak looks right skewed.
> 
> Loans in this data-set took only 3 values 1, 3 or 5 years. Short term loans (1 year) didn't typically exceed 25k $, whilest 3 and 5 year loans took a larger range of values and reached a maxiumum of 35k.


## Key Insights for Presentation

> The changes I included in my slide deck was only polishing. I seprated some figures from facetplots and polished them by added labels and a meaningful title.
> 
> The distribution of Borrower rates looks roughly normal but with an isolated peak at nearly 0.32. The bulk of the interest rate is between 0.12 and 0.2 and the bulk other than the peak looks right skewed.
> 
> Loans in this data-set took only 3 values 1, 3 or 5 years. Short term loans (1 year) didn't typically exceed 25k $, whilest 3 and 5 year loans took a larger range of values and reached a maxiumum of 35k.
> 
> We can see that Non-homeowners tended to get the vast majority of the small loans with high borrower rates. Their small listings took a large range of borrower rates with most of them from 0.15 to 0.35.
> 
> Homeowners, on the other hand, had most of their small listings with a borrower rate of around 0.3.


## Data

> [Loan Data from Prosper](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000) with [Prosper Data Dictionary to Explain Dataset's Variables](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)
