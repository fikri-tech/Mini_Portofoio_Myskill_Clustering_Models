Title: Customer Product Ownership Analysis with Clustering

## Problem Statement
Many businesses struggle to identify the right strategy for offering products that suit the segments of potential customers.

## Objective
To develop a Clustering Model that identifies product ownership based on customer demographics, focusing on FundFusion service users, with a Silhouette Score exceeding 0.7.

## Variables
1. **GCIF**: Unique Customer Identifier
2. **Area**: Customer Location (Jakarta, Bogor, Bandung, Surabaya, Jogja, Solo)
3. **Opening_Channel**: Touch Points used by customers to open products (Branch, Telemarketing, Digital Application, Internet Banking)
4. **Vintage**: Duration of Customer Relationship (Since account opening)
5. **Age**: Customer Age
6. **Gender**: Male (1) & Female (0)
7. **Marital_Status**: Marital Status (Single: 0, Married: 1, Divorced: 2, Widow/Widower: 3)
8. **Number_of_Children**: Number of Customer's Children (numeric)
9. **Education**: Highest Education Level (No Formal Education: 0, Elementary: 1, Junior High: 2, High School: 3, Bachelor: 4, Master: 5, Doctorate: 6)
10. **Savings_Product**: Ownership Status (Yes/1, No/0)
11. **Deposit_Product**: Ownership Status (Yes/1, No/0)
12. **Credit_Card_Product**: Ownership Status (Yes/1, No/0)
13. **Housing_Loan_Product**: Ownership Status (Yes/1, No/0)
14. **Vehicle_Loan_Product**: Ownership Status (Yes/1, No/0)
15. **Personal_Loan_Product**: Ownership Status (Yes/1, No/0)
16. **Total_Product_Ownership**: Total Number of Owned Products (Sum of Products)
17. **Annual_Income**: Average Annual Income
18. **Total_Relationship_Balance**: Total Customer Assets in the Observation Month Cutoff

## Experiment
1. Grouping based on demographics to uncover product ownership patterns.
2. Grouping based on product ownership to identify patterns based on demographics.

## Deliverables
- Detailed analysis report outlining clusters and insights.
- Python notebook or script for replicating the clustering model.
- Visualizations illustrating demographic and product ownership patterns.
- Recommendations for product offerings tailored to different customer segments.

This project aims to provide actionable insights for product strategy optimization, enabling businesses to better meet the needs of their diverse customer base.
