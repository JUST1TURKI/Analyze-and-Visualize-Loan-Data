# Loan Data Exploration

## Dataset

The Prosper loan dataset consists of detailed information about 113,937 individual loans facilitated by Prosper, covering various aspects of the lending process, borrower characteristics, and loan performance metrics. The dataset has 81 columns, and each row represents a unique loan.

Data Wrangling:
The data wrangling process involved three main steps: data gathering, data assessment, and data cleaning. Unnecessary variables were removed, and certain columns were converted to appropriate data types for streamlined analysis. Tidying the data included splitting date and time components for better handling.

Data Storage:
The cleaned dataset was saved in a CSV file named "prosperLoanData-clean.csv" to facilitate future analysis and modeling.

Data Visualization:
The data visualization phase comprised univariate, bivariate, and multivariate analyses to uncover relationships and patterns within the dataset.


## Summary of Findings

The exploratory data analysis revealed several key insights:

    Strong positive correlation (0.93) between Monthly Loan Payment and Loan Original Amount.
    Borrowers with higher income ranges tend to have larger loans and higher monthly payments.
    Most loans have a term of 36 or 60 months, with 12-month terms being less preferred.
    Around 50% of borrowers are homeowners, while approximately 11% are part of a group.
    Borrowers with verifiable income account for over 92% of the dataset.
    The majority of loans are in good standing or have been successfully completed.
    Loan number, term, and investors show positive correlations with Loan Original Amount.
    Loans are more concentrated around 36 months and loan numbers between 60,000 to 100,000.

## Key Insights for Presentation

For the explanatory analysis, we will focus on the following key insights:

    The strong positive correlation between Monthly Loan Payment and Loan Original Amount.
    The influence of income range on loan amounts and monthly payments.
    Preferred loan terms and their impact on loan amounts.
    Loan status distribution based on borrower characteristics.
    Trends in loan origination periods.

We will present these insights using clear visualizations, including scatter plots, histograms, and countplots. Additionally, we may create new visualizations to further illustrate the relationships and patterns uncovered during the data exploration.

In the explanatory report, we will provide a more focused and coherent narrative, showcasing the most relevant findings to effectively communicate the dataset's implications and potential applications in the lending industry. The aim is to present the insights in a clear, concise, and visually appealing manner, making the report engaging and informative for stakeholders and decision-makers in the financial domain.