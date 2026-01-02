****House Construction Expense Tracker Dashboard**

**🔷 1. Introduction**

Exploring and analyzing housing construction expenses using data analytics.

This construction dashboard offers a clear financial overview of a building project for a 1030 sqft area. It highlights labour costs, material expenses, daily spending, and the current cash position, enabling better monitoring and budgeting. The dashboard provides transparency into where and how funds are being used.

This Power BI dashboard is designed to track and analyze the construction expenses of a residential house project. It offers a comprehensive view of financial metrics, phase-wise progress, actual vs estimated expenses, and provides interactive tools like drillthrough functionality to explore granular data.

The dashboard aims to assist in monitoring budget utilization, identifying cost overruns, and making informed decisions related to materials, labor, and capital expenditure during the different construction stages.

**🔷 2. Background**

This dashboard was created to track the construction expenses of our ongoing housing project. The idea emerged when one of our family members raised a concern about the lack of proper financial records or traditional methods, which could lead to confusion or disputes later. This prompted us to start organizing our construction expenses in a simple, transparent way. Initially, we decided to use Excel to record all transactions. However, we weren’t sure how to structure or store the data effectively. We began with three separate worksheets: Material Expenses, Labour Expenses, and Other Pre-Expenses. While this helped capture the data, visualizing it in Excel proved to be ineffective. To improve visibility, we shifted to Power BI. But we soon faced another challenge—since the data was spread across three unconnected tables without any primary or foreign keys, it was difficult to model relationships between them. To solve this, we merged all three worksheets into a single consolidated table. We added a new column to indicate the type of expense (Material, Labour and Pre construction expediture), allowing us to build a more efficient and unified dashboard in Power BI. As this is an ongoing project, the dashboard is continuously updated and modeled on a daily basis. To streamline data entry, we moved our storage to Google Sheets, which enables real-time updates from any device via the cloud. Now, any family member who spends on construction can instantly log the expense, and by simply refreshing the Power BI report, the dashboard stays up-to-date.

The construction project is currently in progress, with the foundation work completed and initial phases already incurring expenses. The data source is Google Sheets, where the user manually logs expenses under various categories such as:

- Materials (e.g., cement, bricks)
- Labor payments
- Capital assets (e.g., tools, machinery)
- Pre-construction costs (legal, architect fees, etc.)
  
The project is being funded by a loan, and therefore, tracking expenditure versus available funds is critical. This dashboard serves as a live monitor of financial performance, with the ability to drill down into each phase or category for deeper insights.

<img width="1332" height="751" alt="image" src="https://github.com/user-attachments/assets/7548aa29-2a20-4df7-8524-bf1f96271dc4" />

<img width="792" height="747" alt="image" src="https://github.com/user-attachments/assets/6ec7bce3-f661-40d3-b64f-0e48c49fd328" />















**🔷 3. Key Points in Detail**

I created this dashboard to keep track of each phase of my house construction, comparing estimated vs actual costs. It clearly shows how much loan was credited, how much I’ve spent, and which phases are over or under budget. This helps me plan better.


**🔷 4. Usage of DAX (Data Analysis Expressions)**

I used DAX to calculate key metrics like budget used, loan credited, and the ratio of labour vs material. It also helped me apply filters, track progress by phase, and show status changes automatically as work moves from ‘yet to start’ to ‘completed’.

**🔷 5. Graphs & Visualizations Used**

I used line charts for daily and overall expenses, a donut chart to compare loan vs spending, and a stacked bar chart for forecasts. There's also a detailed table with color coding to easily spot budget differences. Filters make it easy to view specific info.

- Bar Chart: Estimated vs Actual expenses (Variance by Phase)
- Donut Chart: Loan Credited vs Spent
- Line Chart: Material vs Labour (Cumulative Expenses Over Time)
- Forecast Line Chart: Predictive spend tracking
- Card Visuals: Key financial metrics
- Matrix/Table: Construction Phase Status + Drillthrough
  
**🔷 6. Conclusion**

This dashboard really helped me stay in control of home construction budget. It gave me clarity on where my money is going and helped me make informed decisions. I believe anyone building a house can benefit from something like this to avoid surprises.

This dashboard is a powerful and interactive tool that brings visibility, control, and insight to the complex financial side of house construction. With effective use of DAX calculations, visual storytelling, and drillthrough-enabled insights, it:

- Simplifies budget tracking
- Enhances accountability for every rupee spent
- Supports future planning through forecasting
- Enables phase-wise and category-wise auditing
It is especially useful for homeowners managing their own construction projects or for civil contractors and financial planners who need to monitor cost vs budget with daily or weekly updates.

**🔷 Tools & Technologies**

- Power BI (DAX, Power Query) and Google Sheet
- AI

**🔷 How to Use**

1. Download the `.pbix` file
2. Open it in Power BI Desktop
