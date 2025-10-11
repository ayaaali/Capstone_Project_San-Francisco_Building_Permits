# Capstone_Project_San-Francisco_Building_Permits


## Project Overview
This project analyzes the San Francisco Building Permit Applications dataset to uncover insights into the city’s construction activity, cost trends, approval delays, and neighborhood growth patterns.
The main goal is to identify factors affecting permit approval times and support data driven decision-making for improving the efficiency and transparency of the permitting system.

## Objectives
1- Identify the most and least common permit types in San Francisco.

2- Analyze the average approval time for each permit type.

3- Identify the most common number of stories in building applications.

4- Examine yearly trends in permit applications.

5- Analyze permit types by cost (estimated and revised).

6- Identify top neighborhoods by number of permits and proposed units.

## Dataset Description
Source: Kaggle – San Francisco Building Permit Applications Data

Data Link: https://www.kaggle.com/datasets/aparnashastry/building-permit-applications-data

Period Covered: 2012 – 2018

Records: Over 190,000 permits

Columns: 43 fields related to construction permits

## Data Cleaning and Preparation
1- Converted date columns to datetime format.

2- Handled missing and null values across multiple fields.

3- Standardized text entries (e.g., replaced "Y" with "True").

4- Removed duplicate records.

5- Calculated new fields:

Days_to_Issue → Permit approval time.

Year → Extracted from Permit Creation Date.

6- Filtered out outliers and unrealistic date or cost values.

## Key Insights
1- Most Common Permit Type: OTC Alterations – small projects with quick approvals.

2- Slowest Approvals: New Construction permits – averaging around 479 days.

3- Most Common Building Heights: 1–10 stories dominate applications due to zoning and earthquake safety.

4- Peak Activity Year: 2015, followed by a decline in 2018.

5- Top Neighborhood: Financial District – with over 20K permits filed.

6- Highest Costs: New Construction permits, reaching millions per project.

7- Trends: Smaller, low-cost permits are approved faster; larger ones face longer delays.

## Tools and Techniques

1- Data Cleaning & Analysis: Python (Pandas)

2- Visualization: Matplotlib, Seaborn, Power BI

3- Feature Engineering: Approval time, year extraction, cost normalization

## Conclusions
1- Complex and high cost permits take significantly longer to approve.

2- Most construction occurs in a few high demand neighborhoods.

3- Administrative delays vary year by year.

4- Smaller permits dominate due to their simplified processing requirements.

## Recommendations
1- Digital Streamlining: Automate permit tracking and document verification.

2- Resource Prioritization: Assign more staff to handle complex applications.

3- Transparency: Publish expected approval timelines for each permit type.

4- Performance Audits: Regularly review long-delay categories to reduce backlogs.

5- Urban Planning Insights: Use neighborhood trends to guide zoning and development policies.
