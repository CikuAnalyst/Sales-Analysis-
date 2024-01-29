# Sales Analysis
---
## An end to end Sales Analysis Project using MsSQL and PowerBi 

## Table of Contents 
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references) 

### Project Overview
---
This Data Analysis Project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![pie chart eg](https://github.com/CikuAnalyst/Documenting_Example/assets/132788939/631edf68-a2c6-4b71-aab5-5ef7e1b20724)


### Data Sources
Sales Data: The primary data set used for this analysis is the "sales_data.csv" file, containing detailed information about each sale made by the company.

### Tools 
- Excel - Data Cleaning
   - [Download here](https://microsoft.com)
- SQL Server
   - [Download here](https://azure.microsoft.com/en-gb/products/azure-sql/managed-instance/?&ef_id=_k_Cj0KCQiAtaOtBhCwARIsAN_x-3Lctv0lZSHFlwiSdXfgrVr-DWLt72NCWcUIdr4lXTDSLI0H4nqQ7MUaAkfBEALw_wcB_k_&OCID=AIDcmm4z26duq7_SEM__k_Cj0KCQiAtaOtBhCwARIsAN_x-3Lctv0lZSHFlwiSdXfgrVr-DWLt72NCWcUIdr4lXTDSLI0H4nqQ7MUaAkfBEALw_wcB_k_&gad_source=1&gclid=Cj0KCQiAtaOtBhCwARIsAN_x-3Lctv0lZSHFlwiSdXfgrVr-DWLt72NCWcUIdr4lXTDSLI0H4nqQ7MUaAkfBEALw_wcB)
- PowerBI - Creating reports
   - [Download here](https://www.microsoft.com/en-us/power-platform/products/power-bi)

### Data Cleaning/Preparation
  In the initial data preparation phase, we performed the following tasks:
 1.  Data loading and inspection.
 2.  Handling missing values.
 3.  Data cleaning and forecasting.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions such as:
 - What is the overall sales trend?
 - Which prospects are top sellers?
 - What are the peak sales periods?

### Data Analysis 

```sql
SELECT " FROM table1
WHERE cond = 2;
```
### Results/Findings
The Analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LIV) should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively
  
### Limitations
I had to remove all zero values from the budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between budget and the number of votes with revenue.

### References 
1. SQL for Businesses by Herman Ross
2. [Stack Overflow](https://stack.com)

😃💻🛒

🔼

|Heading 1|Heading 2|
|--------|--------|
|Content|Content2|
|Python|SQL| 

