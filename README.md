Agency Budget Spending Analysis
Overview
This project focuses on analyzing the budget spending patterns of various government agencies over different fiscal years. The dataset provides a snapshot of financial allocations, including total funds (ALL FUNDS), city-specific funds (CITY FUND), and agency-specific details.

Dataset Snapshot
The dataset includes the following columns:

PUBLICATION DATE: The date when the data was published.
FISCAL YEAR: The fiscal year associated with the data.
AGENCY CODE: A code representing the specific government agency.
AGENCY NAME: The name of the government agency (e.g., Department of Education).
ALL FUNDS: The total budget allocated to the agency in the fiscal year.
CITY FUND: The portion of the budget funded by the city.
REMARK: Additional notes or comments (often contains NaN values).
Sample Data
PUBLICATION DATE	FISCAL YEAR	AGENCY CODE	AGENCY NAME	ALL FUNDS	CITY FUND	REMARK
20171201	2017	040	Department of Education	23508038	11116952	NaN
20171130	2009	040	Department of Education	17903053	7259066	NaN
20171130	2005	040	Department of Education	13871184	5605073	NaN
20171130	2008	040	Department of Education	16977034	6997793	NaN
20171130	2015	040	Department of Education	20999365	9739990	NaN
Work Done
Data Preparation
Column Selection: Selected relevant columns to focus the analysis on budget allocations and agency details.
Spending Pattern Analysis: Analyzed the spending patterns across different fiscal years to identify trends and anomalies.
High Variance Areas: Identified the top 10 areas with high variance in budget allocations and provided reallocation suggestions.
Exploratory Data Analysis (EDA)
Variance Over the Years: Plotted the variance in budget allocations over the years to visualize trends.
Top 10 Areas by Variance: Created bar plots to highlight the top 10 areas with the highest budget variance.
Reporting
Summary Report: Compiled a summary report with key findings, including reallocation suggestions based on the variance analysis.
