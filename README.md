# Project--Insurance-Data-Analysis-Power-BI-


# Insurance-Dashboard

A brief description of what this project does and who it's for

### Dashboard Link: https://shorturl.at/z4hx4

## Problem Statement

This dashboard helps insurance companies gain actionable insights into their operations. By analyzing customer demographics, policy sales, claim patterns, and revenue trends, the company can identify areas of improvement and growth opportunities. 

For example, understanding which regions or agents perform best in policy conversion, or which policy types result in more claims, allows data-driven decision-making. It also enables the business to detect risk-prone segments and optimize strategies accordingly.

With a clear view of total policies, revenue, and claims ratios, the business can improve underwriting standards, streamline claims processes, and enhance overall customer satisfaction.

---

### Steps followed 

- **Step 1**: Loaded Excel data into Power BI Desktop.
- **Step 2**: Cleaned and transformed data using Power Query Editor – verified column quality and ensured data types were correctly assigned.
- **Step 3**: Verified missing/null values and handled them appropriately in calculations (e.g., ignored nulls in claim count and premium calculations).
- **Step 4**: Created calculated columns and DAX measures for:
  - Total Revenue
  - Claim Ratio
  - Average Premium
  - Customer Segmentation (based on age, premium bands, etc.)
- **Step 5**: Designed a multi-page interactive dashboard with slicers for:
  - Region
  - Agent
  - Policy Type
  - Customer Gender
- **Step 6**: Built KPI cards to show high-level insights:
  - Total Policies
  - Number of Claims
  - Total Revenue
- **Step 7**: Added visualizations including:
  - Bar and Column Charts for regional and agent performance
  - Pie Charts for customer demographics
  - Line Chart for premium trends over time
  - Stacked visuals for policy and claim comparison
- **Step 8**: Applied themes and formatting for clarity and brand alignment.
- **Step 9**: Published the report to Power BI Service for stakeholder access.

---

# Snapshot of Dashboard (Power BI Service)

![Image](https://github.com/user-attachments/assets/414245e8-69f6-45fd-b2bc-3411792b4c91)

# Insights

Following key insights were obtained from the analysis:

### [1] Customer Demographics
- Majority of customers fall within the **25–50** and **50–65** age groups.
- Gender distribution is relatively even, with a slight tilt toward male customers.
- Most policies are sold in urban and semi-urban regions.

### [2] Policy and Claim Patterns
- Certain policy types (e.g., **Health** and **Auto**) have higher claim ratios.
- Agents in **Region A** and **Region C** have the highest policy conversion rates.
- A few agents underperform consistently and may need training or review.

### [3] Revenue and Premium Trends
- Revenue is concentrated around high-premium policies, though they constitute a smaller customer segment.
- Premium trends show seasonal variations, peaking during certain months.

### [4] Claims Insights
- A significant proportion of claims originate from younger policyholders, especially in health insurance.
- Claim amounts are higher in specific policy types, necessitating risk recalibration.

---

## Technologies Used

- Power BI Desktop
- DAX for calculated columns and KPIs
- Excel (for data import)

---

## Future Improvements

- Add predictive modeling for high-risk customers using Python integration.
- Embed the dashboard into a web portal via Power BI Service.
- Include year-over-year (YoY) and quarter-over-quarter (QoQ) growth measures.
- Enhance interactivity with drill-through pages and tooltips.

---

## Author

- **Rituthakur-29**
- [GitHub Profile](https://github.com/rituthakur-29)
