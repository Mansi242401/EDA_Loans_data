# Exploratory Data Analysis (EDA) of Prosper Loan Dataset
This repository contains an in-depth Exploratory Data Analysis (EDA) of the Prosper Loan dataset. The analysis aims to uncover valuable insights and patterns within the dataset and provide a comprehensive understanding of the loan data.

## Dataset Description
The Prosper Loan dataset consists of 113,937 loans with 81 variables on each loan. The variables include loan amount, borrower rate (interest rate), loan status, borrower income, and many others. The dataset provides a rich source of information to explore and analyze the factors influencing loan performance and borrower characteristics.

## Files
prosper_loan_eda.ipynb: Jupyter Notebook containing the complete EDA process, including data cleaning, visualization, and analysis.
prosper_loan_insights.ipynb : Jupyter Notebook containing the key insights that can be draw from this analysis.
prosperLoanData.csv: CSV file containing the original Prosper Loan dataset used in the analysis.

## Analysis Highlights
1. Data Cleaning: The analysis begins with thorough data cleaning, handling missing values, and transforming variables to ensure data quality and consistency.
2. Descriptive Statistics: Key descriptive statistics are calculated to provide an overview of the dataset, including summary statistics, distribution of variables, and correlation analysis.
3. Visualization: Various visualizations, such as histograms, scatter plots, and bar charts, are used to explore relationships between variables and uncover trends and patterns.
4. Loan Performance Analysis: The analysis focuses on loan performance metrics, investigating factors influencing loan defaults, late payments, and successful repayments.
5. Borrower Characteristics: Insights are derived from exploring borrower demographics, income levels, employment status, and credit ratings to understand their impact on loan outcomes.
6. Interest Rate Analysis: The analysis delves into the relationship between interest rates and loan characteristics, identifying factors affecting interest rate variations.
7. Key Findings: A summary of the most significant findings and insights gained from the analysis.

## Insights and Conclusions
The EDA reveals several key insights and conclusions:

1. Relationship between loan status and interest rates: Interest rates are generally lower for completed and current loans, while past-due, defaulted, and charged-off loans tend to have higher interest rates.
2. Impact of borrower occupation on interest rates: Certain occupations, such as teachers, homemakers, bus drivers, and flight attendants, are charged higher interest rates compared to others.
3. Influence of loan term on interest rates: Long-term loans (5 years) generally have lower borrower APRs compared to shorter-term loans.
4. Relationship between borrower credit rating and interest rates: Borrowers with higher credit ratings tend to receive lower interest rates, indicating a clear inverse relationship.
5. Other interesting relationships: The analysis uncovers relationships between variables such as occupation and stated monthly income, credit rating and trade delinquency, and income verification and loan status.

These insights provide valuable information for lenders, borrowers, and stakeholders in the loan industry to make informed decisions and understand the factors affecting loan performance.

Please refer to the prosper_loan_eda.ipynb notebook for a detailed analysis, code implementation, and visualization.

## Getting Started
To run the Jupyter Notebook and reproduce the analysis, follow these steps:

1. Clone this repository to your local machine or download the ZIP file.
2. Install the required Python packages listed in the requirements.txt file.
3. Open the prosper_loan_eda.ipynb notebook using Jupyter Notebook or JupyterLab.
4. Run the notebook cells sequentially to execute the analysis and visualize the results.
5. Feel free to explore, modify, or extend the analysis based on your needs and interests.

## Dependencies
The analysis was performed using Python 3.7 and the following libraries:

Pandas
NumPy
Matplotlib
Seaborn
Ensure that these packages are installed before running the notebook.

## License
The Prosper Loan dataset used in this analysis is publicly available and subject to its own licensing terms. Please refer to the dataset source for more information.

## Acknowledgments
The Prosper Loan dataset is provided by Prosper Marketplace, Inc. The analysis and insights presented in this repository are solely derived from the dataset.

## Contact
For any questions, suggestions, or collaborations, please feel free to reach out to me at mansivermani1@gmail.com
