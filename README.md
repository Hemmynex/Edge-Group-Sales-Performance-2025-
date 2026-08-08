# Edge-Group-Sales-Performance-2025-
Edge Group Sale Performance (2025) by Idowu Emmanuel
<img width="931" height="423" alt="Corrected R Dashboard" src="https://github.com/user-attachments/assets/b7042e6c-7e78-4853-92b6-c93795375312" />

Prepared by:
Idowu Emmanuel

Tool Used:
Microsoft Excel

Dashboard Title:
Edge Group Sales Performance by 2025

Industry:
Retail / Supermarket

Table of Contents
Introduction
Story of Data
Data Splitting and Preprocessing
Pre-Analysis
In-Analysis
Post-Analysis and Insights
Data Visualizations & Dashboard
Recommendations and Observations
Conclusion
References
Appendices
Introduction

Objective of the Project

The primary objective of this analysis is to evaluate Edge group 2025 sales performance across four key dimensions — regional distribution, salesperson productivity, product category contribution, and temporal sales trends. The analysis aims to identify performance gaps, concentration risks, and strategic opportunities that can inform commercial decision-making for the 2026 fiscal year.

Problem Being Addressed

Edge group operates across four regions (North, East, South, West) with eight salespersons managing accounts across multiple US states. Despite generating a total annual revenue of $435,066.16 across 369 transactions, preliminary observation suggests that performance is heavily concentrated in a small number of regions, salespersons, customers, and product categories. This analysis seeks to answer the following core questions:

● Which regions, salespersons, and product categories are driving the most revenue?

● Where are the significant performance gaps and what is causing them?

● What seasonal patterns exist in the monthly revenue trend?

● What strategic actions can be taken to improve revenue balance and reduce concentration risk?

Key Datasets and Methodologies

The analysis is based on a single primary dataset containing 369 transaction records spanning the full 2025 calendar year. The following analytical methods were employed in Microsoft Excel:

● Pivot Tables — for aggregating revenue by region, salesperson, product category, customer, and month

● Data Slicers — for interactive filtering across dimensions

● Charts and Visualizations — including pie charts, bar charts, treemaps, line charts, and geographic maps

● Dashboard Design — consolidating all key metrics into a single interactive view

Data Source

The dataset is an internal sales transaction record for Edge group.

Data Collection Process

The data was provided in a pre-compiled Microsoft Excel workbook containing a structured transaction table.

Data Structure
Each row represents a completed sales transaction.

The dataset contains the following fields:

Customer
Product
Product Category
Sales Amount
Region
City
Ship City
Sales Representative
Month
Revenue
Important Features and Their Significance

● Revenue — the primary dependent variable and the central metric of this entire analysis

● Region — enables geographic performance comparison and identifies where commercial concentration lies

● Salesperson — links individual productivity to overall revenue outcomes

● Category — reveals which product lines are driving and which are lagging in commercial contribution

● Order Date — enables temporal analysis including monthly trends and seasonality identification

● Ship City — allows city-level geographic revenue mapping and market penetration analysis

Data Limitations or Biases

● Shipped Date: 78 missing values — limits analysis of actual delivery timelines and shipping efficiency

● Shipper Name: 39 missing values — reduces ability to fully evaluate shipper performance

● Payment Type: 102 missing values — the largest gap, limiting payment behavior analysis

● Product Name and Unit Price: 3 missing values each — minor but noted for completeness

● The dataset covers only one fiscal year (2014), limiting multi-year trend and year-over-year comparisons

DATA SPLITTING AND PREPROCESSING

Data Cleaning

The following cleaning steps were performed before analysis commenced:

Removed duplicate records.
Standardized product and customer names.
Corrected inconsistent text formatting.
Verified numerical values.
Removed blank rows.
Ensured consistent date formatting.
Handling Missing Values

· Missing values were handled through:

· Excel Filters

· IFERROR functions

· Blank cell validation

· Removal of incomplete records where necessary

Data Transformations

● Month extraction: A Month column was derived from Order Date using the Excel MONTH() function to enable monthly trend analysis

● Revenue aggregation: Pivot tables were created to sum Revenue by Region, Salesperson, Category, Customer, Ship City, and Month

Data Splitting — Dependent and Independent Variables

Independent Variables
Customer
Product Category
Sales Representative
Region
City
Ship City
Month
These variables explain the factors influencing sales performance.

Dependent Variable

Revenue

It is the primary outcome being measured and explained

Industry Context

This dataset belongs to the retail and wholesale distribution/E-commerce industry, specifically a multi-regional consumer goods distribution business operating in the United States.

Stakeholders

● Senior Management / Executive Team — primary audience for the dashboard and recommendations

● Regional Sales Managers — responsible for acting on region-level performance insights

● Individual Salespersons — accountable for their personal revenue targets

● Product / Category Managers — responsible for portfolio mix and product-level strategies

● Marketing Department — uses customer and geographic insights for campaign targeting

Value to the Industry

This analysis enables management to;

Increase profitability
Improve regional sales strategy
Monitor customer performance
Evaluate employee productivity
Improve logistics planning
Optimize product inventory
PRE-ANALYSIS

Key Trends Identified

Write on Medium
● Total annual revenue of $435,066.16 across 369 transactions is heavily concentrated in a small number of regions, salespersons, and customers.

● North region shows a significantly wider bar in early data exploration, suggesting it outperforms the other three regions considerably

● December and June appear as the two highest-revenue months in a preliminary scan of monthly order dates — indicating a seasonal double-peak pattern

● Company D appears repeatedly with high-value transactions in early data scrolling — flagging it as a likely top customer before pivot confirmation

Potential Correlations

Possible relationships expected included:

· Region vs Revenue

· Customer vs Revenue

· Month vs Revenue

· Product Category vs Revenue

· Sales Representative vs Revenue

Initial Insights

● The South region appears to be a one-salesperson operation (Anne Larsen) — raising an immediate question about coverage risk before analysis confirms the scale of dependency

● Jan Kotas’s transactions appear infrequent and low-value in early data exploration — suggesting an outlier performance position at the bottom of the salesperson ranking

● The absence of transactions in many US states (visible in the raw address data) suggests geographic concentration that a map visualization will likely confirm

IN-ANALYSIS

Regional Performance Analysis

North as the dominant region at $141,680.34 contributing 32.6% of total revenue. East follows at $108,275.51, South at $93,858.33, and West at $91,251.98. The North-to-West gap of $50,428.36 represents the widest regional performance spread in the dataset. South and West are separated by just $2,606.35, effectively tied at the lower end of regional performance.

Salesperson Performance Analysis

Nancy Freehafer leads all salespersons at $104,252.34, followed by Anne Larsen at $93,858.33. Together they account for 45.5% of total revenue, a concentration that creates significant key-person risk. Jan Kotas sits at $16,350.50 which is less than one-sixth of Nancy’s output representing an 8x performance differential within the same team. The middle tier (Andrew Cencini through Michael Neipper) spans $37,428 to $67,180.50, showing a gradual decline consistent with the trend line visible in the performance chart.

Product Category Analysis

Beverages leads all categories at $110,577.11, the single largest product category by a clear margin. Sauces follows at $69,000, Jams & Preserves at $51,541, Dairy Products at $33,129.60, Dried Fruit & Nuts at $27,999.50, and Canned Meat at $25,465.60. At the individual product level, Coffee ($75,486) and Curry Sauce ($69,000) are the top two products, confirming that a small number of SKUs drive disproportionate revenue within the Beverages and Sauces categories.

Customer Analysis

Company D is the top customer at $67,180.50, followed by Company H ($50,208.35) and Company BB ($43,713.00). The top three customers together contribute approximately $161,101.85 which is 37% of total revenue from just three accounts. Company K sits at the bottom of the top-10 at $21,937.08 less than a third of Company D’s value suggesting the top-10 list contains accounts of significantly varying commercial weight.

Monthly Analysis

December is the peak month at $66,642.78, with June as the mid-year peak at $55,601.61. February ($19,985.50) and April ($20,771.79) are the two weakest months, forming a pronounced Q1 trough. The annual pattern forms a W-shape — rise, fall, rise, fall, rise — with two clear peaks bookending the year. This seasonal pattern has direct implications for inventory planning, sales targeting, and resource allocation.

Analysis Techniques Used

● Pivot Tables — used for all revenue aggregations by region, salesperson, category, customer, month, and city

● Slicers — applied to the Full Dashboard sheet for interactive cross-dimensional filtering

● Conditional Formatting — applied to identify performance tiers in salesperson and regional data

● Slicer: used for in-depth filtering for further analysis.

● Charts — Bar, Pie, Treemap, Line, Map, and Donut charts created from pivot table outputs

POST-ANALYSIS AND INSIGHTS

Key Findings

Total Annual Revenue- $435,066.16 across 369 transactions

Top Region- North — $141,680.34 (32.6% of total)

Bottom Region- West — $91,251.98 (21.0% of total)

Top Salesperson- Nancy Freehafer — $104,252.34

Top Product Category- Beverages — $110,577.11

Top Customer- Company D — $67,180.50

Peak Month- December — $66,642.78

Top City- New York — $67,180.50

Comparison with Initial Findings

The pre-analysis hypotheses were largely confirmed through formal analysis. North’s dominance, the two-peak seasonal pattern, Company D’s top customer status, and Jan Kotas’s outlier position were all validated. The most counter-intuitive finding was the near-identical performance of South ($93,858) and West ($91,251) which were assumed to be more differentiated before analysis. The discovery that Green Tea is the only four-region product was also unexpected and represents a strategically significant insight that was not visible in the raw data.

DATA VISUALIZATIONS & CHARTS

Dashboard Overview

All charts and visualizations were consolidated into a single interactive Full Dashboard in Microsoft Excel. The dashboard includes six KPI cards (Top Performing Month, Customer of the Year, Best Region by Revenue, Top Grossing State, Product of the Year) connected to slicers for Product and Salesperson filtering. The following charts are included:

Chart Types

Sales by Region- Pie Chart

Performance by Salespersons- Horizontal Bar

Product Category Performance- Treemap

Sales Trend- Area Line Chart

Ship Cities Performance- Funnel chart

Ship Cities by Revenue- Radar / Donut

States’ Performance- Geographic Map

RECOMMENDATIONS AND OBSERVATIONS

1. Protect and Manage the North Region’s Concentration Risk

North contributes 32.6% of total revenue from a single region. While this reflects strong performance, it represents a concentration risk. No single region should exceed 30% of total revenue as a strategic target. Invest in South and West to close the performance gap, and ensure North has documented coverage plans for key accounts in the event of salesperson disruption.

2. Address the Jan Kotas Performance Gap Immediately

Jan Kotas’s $16,350.50 revenue against a team average of approximately $54,383 is the most pressing individual performance issue in this dataset. His account base is limited to a single customer (Company CC) in Denver, CO. A formal performance review should determine whether the issue is structural (territory, account base) or performance-related, with a 60–90day improvement plan implemented immediately either way.

3. Build a Coverage Plan for Anne Larsen in the South

Anne Larsen is the sole salesperson serving the entire South region. At $93,858.33, South is the third-largest region — too commercially significant to be covered by a single person. A secondary salesperson or account backup arrangement must be established to protect South’s revenue in the event of absence, resignation, or role change.

4. Develop a Q1 Revenue Stimulus Strategy

February ($19,985.50) and April ($20,771.79) represent the two weakest months of the year less than a third of December’s revenue. A structured Q1 stimulus plan including early-year promotions, volume incentives for key customers, and targeted outreach campaigns should be designed and deployed in January to prevent the annual revenue trough from deepening further.

5. Expand Green Tea Distribution and Investigate Coffee/Curry Sauce East Gap

Green Tea’s universal four-region distribution makes it the most strategically stable product in the portfolio. Volume expansion in underperforming cities should be prioritized. Coffee and Curry Sauce are absent from the East region despite New York and Chicago being two of the largest commercial markets in the US. Andrew Cencini and Laura Giussani should be assigned specific product introduction targets for both products in Q3–Q4 to align with their national peak months.

6. Leverage December and June Peaks Strategically

December and June together account for approximately 28% of annual revenue. A formal seasonal preparation calendar beginning 6–8 weeks before each peak — should govern stock positioning, promotional activity, and sales team capacity planning to maximize capture of these two high-value windows.

CONCLUSION

Key Learnings

This analysis confirmed that Edge group 2014 commercial performance is structurally sound but heavily concentrated. North, Nancy Freehafer, Beverages, Company D, and December are the five pillars carrying a disproportionate share of the business. The analytical process — from raw data through pivot tables, slicers, and dashboard visualization successfully transformed 369 transaction records into a clear strategic picture that management can act on with confidence.

The most significant learning from this project is that data does not speak for itself — it requires structured analytical methodology, appropriate visualization choices, and disciplined interpretation to generate insight. The combination of pivot tables, slicers, and a multi-chart dashboard proved to be an effective and sufficient toolset for answering all core business questions from this dataset using Microsoft Excel alone.

Limitations

● Single-year dataset limits ability to identify multi-year trends or validate whether 2014 patterns are consistent with historical performance

● Missing values in Payment Type (102 records) prevent complete analysis of payment behavior across the customer base

● No customer acquisition date or tenure data — limits ability to distinguish new vs. established account performance

● No cost data (beyond shipping fees) — prevents margin-level analysis; Revenue is the only profitability proxy available

● Geographic analysis is limited to shipped-to addresses — no data on where customers are headquartered or where demand is generated

Future Research

● Incorporate 2015 data to perform year-over-year comparison and validate whether the W-shaped seasonal trend is consistent across years

● Add product cost data to enable gross margin analysis moving beyond revenue to profitability at the category and product level

● Explore customer segmentation analysis using demographics or purchase frequency data to refine the account management strategy

● Investigate the Canned Meat and Dried Fruit & Nuts underperformance in greater depth including whether regional distribution gaps or pricing issues are the primary driver

REFERENCES & APPENDICES

References

● Dataset: Edge group Sales Dataset — provided as part of the Vephla University Data Analytics Programme curriculum (2024)

● Tool: Microsoft Excel

● Institution: Vephla University — Data Analytics Programme, 2024–2025

● Framework: Technical Report Template for Analytical Projects — Vephla University

Appendices

Appendix A: Completed Dashboard Screenshot

Appendix B: Pre-Analysis Board

Appendix C: In-Analysis Board

Appendix D: Post-Analysis Board

Appendix E: Pivot Tables and Pivot Charts

Appendix F: Excel Functions Used

VLOOKUP

SUMIFS

COUNTIFS

IF

IFERROR

Pivot Calculated Fields

Appendix G: Dashboard Components

KPI Cards

Interactive Slicers

Pie Chart

Doughnut Chart

Treemap

Filled Map

Horizontal Bar Charts

Area Chart

This report outlines the full analytical process applied to the Edge Group Sales Performance Dashboard spanning through data preparation, visualization design, and the derivation of actionable business recommendations.
