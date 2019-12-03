# Loan Dataset Exploration and Explanation
## Brijrajsinh Gohil


## Dataset

> The dataset that was made available was a Loan dataset by Prosper which contains around 113,066 rows and 81 columns, so what I was trying to do is to find out the relationships between these features. I initially started by importing data from the provided .csv file, the link is given by Udacity. Then I did some basic data wrangling such as removing duplicated data, converting types to datetime and categorical data types, I used info() function to confirm the validity of the converted data type columns.


## Summary of Findings

> From my visualizations and findings it was observed that BorrowerAPR and BorrowerRate are highly correlated, later I also found out that it had negative correlation with ProsperRating (Alpha), the BorrowerAPR and ProsperScore were also negatively correlated, with increase in BorrowerAPR, it was found out that there is a decrease in ProsperScore. The dataset also contains a high number of loans that are mostly of period with 36 months term loan. A correlation value of 0.932 was also found between LoanOriginalAmount and MonthlyLoanPayment, which can give us an insight that with an increase in Loan Amount there would be a greater number in monthly payments.


## Key Insights for Presentation

> The key insights for the presentation were that, BorrowerAPR and BorrowerRate are strong positively correlated.
  Considering the relationship between BorrowerAPR and ProsperRating(Alpha), it was observed that they are negatively correlated, i.e. with an increase in BorrowerAPR the ProsperRating(Alpha) would decrease.