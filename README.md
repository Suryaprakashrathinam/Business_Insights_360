# Business_Insights_360

Link to the  [course](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance)

Link to the [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDM2OWExN2MtNTMzZC00ZjJhLTgwZjMtNDM1ZDkyY2QyYTU1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
)

## Problem statement

My dashboard tackles a key business challenge faced by a rapidly expanding consumer electronics company, Atliq. Their dependence on Excel for analytics led to performance bottlenecks, no real-time insights, and a major revenue loss in the Latin American market. This dashboard transitions them to a scalable, interactive solution, empowering faster, data-driven decisions.

## Key learnings

- *SQL*
- *PowerBi Desktop*
- *Excel*
- *DAX language*
- *DAX Studio (for optimizing the report)*
- *Project charter file*

## Business-related terms 

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Project Background – AltiQ Hardware

AltiQ Hardware is a rapidly growing company that sells computers and accessories through three key channels: Retailers, Direct Sales, and Distributors. With its recent global expansion, the company ventured into the American market. However, due to decisions based primarily on surveys, intuition, and basic Excel analysis, the move resulted in unforeseen financial losses.

Unlike competitors who leverage dedicated analytics teams to drive strategic decisions, AltiQ lacked a data-driven approach. Recognizing this gap, the company is now prioritizing the development of a robust analytics function to make informed, insight-driven decisions and stay competitive in the global market.

## Project Kick-Off – Key Objectives

The project begins with a kick-off session to establish:

- Purpose: Why is this project being initiated?
- Goals: What business outcomes are expected?
- Scope: What areas of the business and data will be covered?
- Stakeholders: Who are the key users and decision-makers?
- Data Sources: What systems and formats are we working with?
- Challenges: What limitations do we anticipate?
- Success Criteria: How will we measure success?

## Understanding the Data – Before Analysis

Before jumping into analysis, it’s crucial to gain a clear understanding of the data available. This ensures better decision-making, accurate insights, and a structured approach to solving business problems.

### Data Structure Overview

- Dimension Tables
These contain static or descriptive data that provide context to transactional data. Examples include:
  - Customer details (e.g., name, region, segment)
  - Product information (e.g., category, model, brand)

- Fact Tables
These contain transactional or measurable data, which is the core of business analysis. Examples include:
  - Sales transactions
  - Revenue, profit, and quantity sold
  - Channel of sale (Retail, Direct, Distributor)

Understanding the relationship between these tables—usually in a star or snowflake schema—is essential for building meaningful KPIs and dashboards.

## Connecting MySQL to Power BI

Since the project's database is hosted in MySQL, the first step in the analysis process is to import the datasets into Power BI. This is done by establishing a connection using the MySQL connector and providing the required database access credentials (host, port, username, password, and database name).

This setup enables seamless data import and refresh, ensuring that Power BI always reflects the most recent data for accurate and real-time analysis.

## Mockup dashboards

[rough-dashboard-sketch.pdf](https://github.com/user-attachments/files/19975701/rough-dashboard-sketch.pdf)

## Data Model

![Data model](https://github.com/user-attachments/assets/c9e2ba1b-9005-40a9-8dab-38ddffee8ff1)

## Techniques learned

1. Data Collection, Exploration, and Validation: I gained hands-on experience in sourcing and meticulously validating data from diverse sources, ensuring accuracy and reliability.
2. Power Query Mastery: Transforming raw data into actionable insights was made possible through in-depth work with Power Query, cleaning and preparing data for optimal analysis.
3. DAX Proficiency: Mastering DAX (Data Analysis Expressions) allowed me to create complex calculations and extract meaningful patterns, unlocking deeper insights.
4. Data Modelling: I learned the crucial art of building robust data models, forming the foundation for accurate and insightful dashboards.
5. Calculated Columns: I utilised calculated columns, a frequently used DAX function, to add valuable contextual data.

## Home page

![Homepage](https://github.com/user-attachments/assets/2454a481-2b90-4e22-9f9e-58fe08375c59)

## Information page

![Info](https://github.com/user-attachments/assets/37dc2f77-8cc1-492e-9928-3b17b1b57a06)

## About Finance view

Financial Insights: Detailed P&L statements, net sales performance over time, and analysis of top and bottom products and customers.

![Finance view](https://github.com/user-attachments/assets/eb0bce22-b12e-44ef-adbf-f260f94e11e9)

## About Sales View

Sales Performance: In-depth customer and product performance analysis, a performance matrix, and unit economics.

![Sales view](https://github.com/user-attachments/assets/518e9184-8302-42e4-ae7b-e698fa71fd49)

- **Sales trend tooltip**

![Sales trend tooltip_products](https://github.com/user-attachments/assets/f76b30db-0348-408a-a220-bea911bde3f2)

![Sales trend tooltip_customers](https://github.com/user-attachments/assets/82c5757d-ccae-4687-a3e9-6304ed99f671)

## About Marketing View

Marketing Analysis: Performance evaluation of products and identification of new growth opportunities.

![Marketting view](https://github.com/user-attachments/assets/0b73851d-9b84-4a18-b765-ebe1b16440da)

- **Sales trend tooltip**

![Sales trend tooltip_regions](https://github.com/user-attachments/assets/8a4f48cc-82dd-4589-b800-a012a5770aab)

## About Supply Chain View

Supply Chain Optimization: Tools for forecast accuracy, risk management, and operational efficiency.

![Supply chain view](https://github.com/user-attachments/assets/c0106479-b921-4a29-991b-a4b72c5013eb)

## About Executive View

Executive Overview: High-level summaries for strategic decision-making.

![Executive view](https://github.com/user-attachments/assets/ca9b01f6-8d50-4973-806a-09f3dd2ed864)

## Support page

![Support](https://github.com/user-attachments/assets/3445a02e-6f74-4d76-9a7d-e92a172597aa)

## Actionable Insights Through Reporting

This report empowers decision-makers to make informed, data-driven decisions rather than relying on intuition. It not only provides a clear view of business performance but also enables stakeholders to explore and answer a wide range of "why" questions, helping to uncover root causes behind trends, anomalies, and outcomes.

