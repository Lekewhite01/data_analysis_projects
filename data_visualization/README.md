# (Loan outcome dependencies for Prosper loan data)
## by (Olorunleke Akindote-White)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.



## Summary of Findings

> In my exploration, I observed that employed professionals who earn between 25,000 USD and 75,000 USD actually tend to borrow more. Also, most of these people borrow to offset other loans elsewhere. There was also a perceived preference for long-term loans. The available bank card credit and monthly loan payment appeared highly skewed and needed some transformation. A logarithmic transformation was used to normalize the distribution. After which it was easier to draw inferences. There were improved loan outcomes with increasing employment duration and available bank card credit. Lesser loan terms saw better completion rates than others and borrowing increased with increasing income value up until a midpoint beyond which it starts to decline to current and completed loans.
On the financial rates side, the APR, borrower rate and Lender yield seemed to share similar distribtutions. Scatter plots in the bivariate exploration confirm a positive correlation with the only differentiating factor being the cost of the loan to the borrower (other charges added to give APR) unlike borrower rate and lender yield.
Later on, its revealed that even people who are not employed took out loans, most of which defaulted and despite taking out loans for debt consolidation, the affected individuals surprisingly had an appreciable completion rate than most other categories.


## Key Insights for Presentation

> For the presentation, I focus on the influence of employment status, income range and borrower rate on loan outcome. I've chosen borrower rate because current and completed loans fell to the lower boundary of average borrower rate indicating some sort of preference for lower rates amongst borrowers.
The first two factors are presented using a heat map while the third is presented using a boxplot.