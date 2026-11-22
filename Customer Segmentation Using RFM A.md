# Customer Segmentation Using RFM Analysis

## Project Overview

This project was completed as part of the Syntecxhub Internship Program.

The main objective of this project was to analyse customer purchasing behaviour using RFM (Recency, Frequency and Monetary) analysis. By analysing historical transaction data, customers were grouped into different segments based on their purchasing activities.

The analysis was performed using Python in Google Colab, with Pandas for data processing and Matplotlib and Seaborn for data visualisation.

## Project Objectives

- Understand customer purchasing behaviour.
- Clean and preprocess transactional data.
- Calculate Recency, Frequency and Monetary values.
- Assign RFM scores to customers.
- Identify different customer segments.
- Analyse customer distribution and revenue contribution.
- Develop marketing recommendations based on the findings.

## Dataset Information

**Dataset:** Online Retail Dataset

**Original Source:** UCI Machine Learning Repository

**Dataset Page:** https://archive.ics.uci.edu/dataset/352/online-retail

**Dataset DOI:** https://doi.org/10.24432/C5BW33

The dataset contains 541,909 transaction records and 8 original columns, covering transactions from 1 December 2010 to 9 December 2011.

The CSV source used in the Google Colab notebook was:

https://github.com/dbdmg/data-science-lab/raw/master/datasets/online_retail.csv

## Tools and Technologies

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Project Workflow

1. Load and inspect the dataset.
2. Perform data cleaning and preprocessing.
3. Remove duplicate records and cancelled invoices.
4. Handle missing customer IDs and invalid purchase values.
5. Create the TotalPrice column.
6. Calculate customer-level RFM values.
7. Assign RFM scores from 1 to 5.
8. Perform initial customer segmentation.
9. Investigate different RFM score combinations.
10. Refine customer segmentation.
11. Analyse customer behaviour and revenue contribution.
12. Create data visualisations.
13. Develop business recommendations.

## Data Preprocessing Results

| Description | Result |
|---|---:|
| Original records | 541,909 |
| Final cleaned records | 392,692 |
| Unique customers | 4,338 |
| Unique invoices | 18,532 |
| Missing values in cleaned data | 0 |
| Duplicate records in cleaned data | 0 |
| Total purchase value | £8,887,208.89 |

## RFM Analysis

RFM represents three customer purchasing measurements:

- **Recency:** Number of days since the customer's most recent purchase.
- **Frequency:** Number of unique invoices associated with the customer.
- **Monetary:** Total purchase value associated with the customer.

Customers received scores from 1 to 5 for each measurement.

A higher Recency score represents more recent purchasing activity, while higher Frequency and Monetary scores represent more frequent purchases and higher spending.

## Customer Segmentation Results

The final analysis identified eight customer segments.

| Customer Segment | Customers | Percentage |
|---|---:|---:|
| Champions | 941 | 21.69% |
| Loyal Customers | 504 | 11.62% |
| At-Risk Customers | 466 | 10.74% |
| Other Customers | 897 | 20.68% |
| Potential High-Value Customers | 204 | 4.70% |
| Hibernating Customers | 824 | 18.99% |
| Potential Loyalists | 222 | 5.12% |
| New / Promising Customers | 280 | 6.45% |
| **Total** | **4,338** | **100%** |

## Key Findings

- Champions represented 21.69% of customers but generated 64.61% of total revenue.
- Loyal Customers contributed 10.33% of total revenue.
- At-Risk Customers contributed 8.63% of total revenue.
- Potential High-Value Customers represented 4.70% of customers and generated 5.72% of revenue.
- Hibernating Customers represented 18.99% of customers but contributed 2.12% of revenue.

The total revenue analysed was £8,887,208.89.

## Visualisations

The project includes five visualisations:

1. RFM Distributions
2. Customer Segment Distribution
3. Revenue Contribution by Customer Segment
4. Customer Frequency vs Monetary Value
5. Average RFM Scores by Customer Segment

These visualisations help explain customer purchasing patterns and compare the performance of different segments.

## Business Recommendations

- Provide loyalty rewards and exclusive benefits to Champions.
- Encourage repeat purchases among Potential Loyalists and New / Promising Customers.
- Use personalised campaigns to re-engage At-Risk Customers.
- Develop repeat-purchase opportunities for Potential High-Value Customers.
- Use cost-effective win-back campaigns for Hibernating Customers.
- Continue monitoring customer behaviour through regular RFM analysis.

## Limitations

- The dataset contains historical transactions from 2010–2011.
- Records without customer IDs were excluded.
- Cancelled invoices and non-positive purchase quantities or prices were excluded.
- Monetary values represent retained positive purchases and do not account for excluded returns.
- RFM segmentation is based on historical purchasing behaviour and does not directly predict future customer churn.
- Customer segments depend on the selected scoring and rule-based segmentation conditions.

## Conclusion

This project provided practical experience in data cleaning, data analysis, customer segmentation and data visualisation using Python.

The analysis helped identify different customer groups and understand their contribution to business revenue. One of the main findings was that Champions generated a significant proportion of the total revenue.

Overall, the project demonstrated how transactional data can be converted into useful information to support customer relationship management and marketing decisions.

## Internship Information

**Internship Provider:** Syntecxhub

**Project:** Customer Segmentation Using RFM Analysis

**Status:** Completed

