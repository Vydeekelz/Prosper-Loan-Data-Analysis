# Prosper Loan Data Analysis
## by Okechukwu Providence

## Introduction
This main aim of this project is to conduct an exploratory data analysis on a Prosper loan dataset. I used Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, patterns, and relationships. This project has two parts that shows the importance and value of data visualization techniques in the data analysis process.

"In Part I, Exploratory data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables."
"In Part II, Explanatory data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations."

## Prosper Loan data
> The original dataset contained 113937 records and 81 variables but my cleaned dataset contains 76224 loan records with 22 variables. Most variables are numeric in nature while the rest are of object, categorical and bool type.

The variables includes:

- ListingKey: Unique key for each listing
- ListingNumber: The number that uniquely identifies the listing to the public as displayed on the website.
- Term: The length of the loan expressed in months.
- LoanStatus: The current status of the loan: Cancelled, Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, .
- BorrowerAPR: The Borrower's Annual Percentage Rate (APR) for the loan.
- BorrowerRate: The Borrower's interest rate for this loan.
- ProsperScore: A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score. Applicable for loans originated after July 2009.
- Listing_category: The category of the listing that the borrower selected when posting their listing
- Occupation: The Occupation selected by the Borrower at the time they created the listing.
- EmploymentStatus:The employment status of the borrower at the time they posted the listing.
- IsBorrowerHomeowner: A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.
- CreditScoreRangeLower: The lower value of the credit score range of borrower provided by credit agency
- CreditScoreRangeUpper: The upper value of the credit score range of borrower provided by credit agency
- DebtToIncomeRatio: debt/income. capped at 10.01
- IncomeRange: The income range of the borrower at the time the listing was created.
- IncomeVerifiable: Borrower provided documents to prove income
- LoanOriginalAmount: The origination amount of the loan.
- BorrowerState: The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.
- StatedMonthlyIncome:The monthly income the borrower stated at the time the listing was created.
- Recommendations: Number of recommendations the borrower had at the time of listing
- LoanOriginationYear: The date the loan was originated
- LoanOriginationMonth: The Month the loan was originated.


## Summary of Findings
- most people take loans in order to consolidate their debts
- people with high prosper score had debt to income ratio less than 1 and had access to low borrower rates and APRs and high loan amounts.
- being a home owner increases your chances of getting a loan and getting a good deal too.

## Key Insights for Presentation
 My key insight focuses more on the main features of interest: Prosperscore and ListingCategory. The listing category shows that the primary motivation for applying loans were debt consolidation. This suggested that many people requested loans to settle their short term debts or everyday bills while waiting to get enough to make a single bulk long term payment in form of the loan repayment.The prosperscore was a primary determinant in deciding what rates, APRs, loan amounts and terms people could benefit from.  "# Prosper-Loan-Data-Analysis" 
