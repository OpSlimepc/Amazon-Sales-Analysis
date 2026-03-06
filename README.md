# Amazon Sales Dashboard Analysis | Revenue & Product Performance 
Excel Project | Global Amazon Sales Data | From Raw Transactions to Actionable Business Insights


## Table of Contents

-  [Project Overview](#project-overview)
-  [Tools & Technologies](#tools--technologies)
-  [Dataset Overview](#dataset-overview)
-  [Data Preparation](#data-preparation)
-  [Excel Dashboard](#excel-dashboard)
-  [Key Insights](#key-insights)
-  [Recommendations](#recommendations)

---

### Project Overview
This project analyzes Amazon sales transactions to uncover trends in revenue, product performance, discounts, and customer behavior. Using Excel, pivot tables and calculated columns were used to transform raw sales data into actionable insights through interactive visualizations.

---

### Tools & Technologies
- Excel – Pivot tables, formulas, calculated columns, and charts for dashboard creation

---

### Dataset Overview
The dataset contains Amazon transaction records with ~50,000 entries. 

Key columns include:
1. Order ID
2. Order Date
3. Product ID
4. Product Category
5. Price
6. Discount Percent
7. Units Sold
8. Customer Region
9. Payment Method
10. Rating
11. Total Revenue

---

### Data Preparation

1. Created Discounted Column
- A new column was added to categorize items as “Discounted” or “Not Discounted” based on if there's value on discount percent column.
2. Used Pivot Tables for Analysis
- Pivot tables were created to summarize revenue, units sold, and orders by category, product, region, and discount status.
- Aggregations included total revenue, total units sold, total orders, and average ratings.
3. Visualizations
- Charts and graphs were created from pivot tables to provide clear insights for decision-making.

---

### Excel Dashboard

The dashboard includes:
1. KPI Cards (using text box + pivot tables)
2. Revenue Analysis
3. Product Performance
4. Discount Analysis

<img width="1602" height="660" alt="image" src="https://github.com/user-attachments/assets/d7971673-5bef-48f3-a953-ff1512484cdc" />


--- 

### Key Insights
1. Discounted products generate significantly more revenue than non-discounted items.
2. The Middle East records the highest revenue among all regions followed by North America.
3. Revenue peaks in January, drops in February, then fluctuates moderately throughout the remaining months, suggesting a strong start-of-year surge followed by a brief post-holiday slowdown before demand normalizes.
4. Product categories such as Beauty, Books, and Electronics show increased unit sales and revenue in 2023, with Beauty recording the highest increase among them.
5. Payment preferences vary by region: UPI is the most preferred payment method in Asia, Debit Card and Digital Wallet are equally preferred in Europe, Cash on Delivery dominates in the Middle East, and Digital Wallet leads in North America.

---

### Recommendations
1. Continue Strategic Discount Campaigns
   - Since discounted items drive a large portion of revenue, maintaining targeted promotional campaigns can help sustain high sales volumes.
2. Focus Marketing Efforts on High-Performing Regions
   - Regions like the Middle East and North America generate the most revenue, making them strong candidates for expanded marketing and inventory allocation.
3. Capitalize on strong early-year demand
   - Since revenue peaks in January, businesses should launch major promotions, product releases, and marketing campaigns early in the year to maximize this surge in demand.

---

Dataset source:
[Download Here](https://www.kaggle.com/datasets/aliiihussain/amazon-sales-dataset)
