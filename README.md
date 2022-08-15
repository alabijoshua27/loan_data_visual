# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating,prosper score, loan term, borrower's stated monthly income, as well as other features such as borrower's employment status, top 10 occupation and current loan status etc.


## Summary of Findings

> In the exploration, I discovered that the borrower APR is negatively correlated with original loan amount. The borrower APR also decreases with the increasingly prosper rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. It is interesting to also note there is a positive coorelation between "Loan original amount" and "Stated Monthly Income" as well as "Loan original amount" and "Prosper Score". This shows that the higher the stated monthly income, the more money they might borrow which make sense. 
> Also since there is a a positive coorelation between Proper score and Loan original amount, people who borrow more have a high chance of getting higher Prosper score because they earn more and can pay their loan. There is an interaction between prosper rating and term where there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers and most of the prosper ratings are 36 month term. Proportionally, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers.


## Key Insights for Presentation

> Histogram was created to visualize the distribution on borrower's APR percentage. After exploring all possible variables related to BorrowerAPR using some of the characters selected from the list of columns, ProsperScore has the strongest relationship with Borrower's APR (negative correlation). Scatter plot and Heatmap were also created to further confirm that ProsperScore and BorrowerAPR were negatively correlated. The third plot created multiple scatter plots (BorrowerAPR vs Loan Amount) on different prosper ratings. The loan amount increases with better rating while borrower APR decreases with better rating. It is also good to note that the relationship between borrower APR and loan amount turns from negative to slightly positive change when the Prosper ratings are increased. This might be as a result of people with A or AA ratings borrowing more money, but people with lower ratings tend to borrow less amount of money. Decreasing borrowers APR could encourage them to borrow more.

