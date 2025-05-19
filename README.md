# Housing-construction-expense-analysis

## Overview

Exploring and analyzing housing construction expenses using data analytics.
This construction dashboard offers a clear financial overview of a building project for a 1050 sqft area. It highlights labour costs, material expenses, daily spending, and the current cash position, enabling better monitoring and budgeting. The dashboard provides transparency into where and how funds are being used.

### Project Background

This dashboard was created to track the construction expenses of our ongoing housing project. The idea emerged when one of our family members raised a concern about the lack of proper financial records, which could lead to confusion or disputes later. This prompted us to start organizing our construction expenses in a simple, transparent way. Initially, we decided to use Excel to record all transactions. However, we weren’t sure how to structure or store the data effectively. We began with three separate worksheets: Material Expenses, Labour Expenses, and Other Pre-Expenses. While this helped capture the data, visualizing it in Excel proved to be ineffective. To improve visibility, we shifted to Power BI. But we soon faced another challenge—since the data was spread across three unconnected tables without any primary or foreign keys, it was difficult to model relationships between them. To solve this, we merged all three worksheets into a single consolidated table. We added a new column to indicate the type of expense (Material, Labour and Pre construction expediture), allowing us to build a more efficient and unified dashboard in Power BI. As this is an ongoing project, the dashboard is continuously updated and modeled on a daily basis. To streamline data entry, we moved our storage to Google Sheets, which enables real-time updates from any device via the cloud. Now, any family member who spends on construction can instantly log the expense, and by simply refreshing the Power BI report, the dashboard stays up-to-date.

![image](https://github.com/user-attachments/assets/9a2afed4-a1be-453f-8a83-2408631dd60c)


![image](https://github.com/user-attachments/assets/d4fc407a-1cd2-4da2-bfaf-d86abc082d8f)


## Key Features

**1. Anticipated Labour Cost vs Paid**

•	The anticipated labour cost for 1050 sqft is ₹472.50K.
•	However, only ₹66.30K has been paid so far.
•	The Labour Charge Paid Ratio stands at 14.03%, indicating that a major portion of labor payment is still pending.

**2. Cash Utilization Status**

•	A total of ₹5,00,000 has been credited to the bank.
•	Out of this, only ₹191K (₹1.91 lakh) has been spent so far. 
•	The remaining ₹3.08 lakh (72.35%) is available as Cash at Bank, which shows a healthy reserve for upcoming project phases.

**3. Category-wise Expense Overview**

•	Materials Expense: ₹113.42K
•	Labour Charge Paid: ₹66.30K
•	Other Expenses: ₹11.33K 
•	Material cost dominates the current expenditure, especially steel + transportation (₹62.69K) and construction materials (₹18.10K).

**4. Daily Expense Pattern**

•	Highest single-day expense spike was on 3rd May, amounting to ₹5.0 lakh, likely reflecting the initial cash deposit. 
•	Another spike occurred on 15th May (₹97K), possibly for bulk procurement or major payments. 
•	Other dates show minimal or no spending, suggesting intermittent expense activity based on work progress.


## Tools & Technologies
- Power BI (DAX, Power Query,Google Sheet)
- ChatGPT

## How to Use
1. Download the `.pbix` file
2. Open it in Power BI Desktop





