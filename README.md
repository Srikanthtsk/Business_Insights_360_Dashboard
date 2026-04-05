# Business_Insights_360_Dashboard

Power BI DAX Data Modeling  ETL

📌 **Table of Contents
**
* Project Overview
* Tasks Performed
* Key Insights & Recommendations
* Dashboards Preview
* Tools & Technologies
* Skills Demonstrated
* Conclusion

**Project Overview**

This project is a Power BI case study for AtliQ Hardware, a multinational company selling computers and accessories through channels like **Amazon, Flipkart, Croma, and its own stores/e-store.

AtliQ Hardware faced challenges in international markets due to intuition-driven decisions. While the competitors are leveraging data-driven decisions to make a profit. To stay competitive, AtliQ has decided to take a data-driven decision approach. The goal of this project was to build a unified reporting solution in Power BI across Finance, Sales, Marketing, and Supply Chain to empower stakeholders with data-driven insights.

The model integrates data from SQL + Excel, with over 4.8M+ records, and uses a custom fiscal year (Sep–Aug) for accurate reporting.


**Tasks Performed
**


🔹 1. **ETL & Data Cleaning (Power Query)**
Connected to multiple data sources, including SQL Databases and Excel Workbooks.
Removed duplicates, handled null values, standardized column names, and ensured data consistency.
Created calculated columns for business logic (e.g., fiscal year alignment, category grouping).
Ensured data quality checks by validating numbers against benchmark/reference values.

🔹 2. **Data Modeling & Relationship Building**
Designed a star schema with 15+ tables (fact & dimension).
Built relationships between sales, customers, products, regions, and targets.
Created a custom Dim_Date table with fiscal year mapping (Sep–Aug) and defined Q1–Q4 periods for reporting.
Ensured proper filter propagation across dimensions for accurate reporting.

📊 **Data Model Preview:**
<img width="889" height="762" alt="image" src="https://github.com/user-attachments/assets/2bd48b9d-0175-40b6-8735-1ea10828851c" />


🔹 3. **KPI Development (DAX Measures)**
Built Net Sales, Gross Margin (GM), GM%, and P&L Statement using advanced DAX functions.
Implemented Forecast Accuracy to compare actuals vs predictions.
Created variance measures to track performance vs targets.
Designed Target Tolerance KPIs to highlight customers with high GM% variance for the Sales team prioritization.

🔹 4. **Dashboard Design & Reporting**
Developed Sales, Finance, Marketing, and Supply Chain dashboards.
Created an Executive Dashboard – consolidated view of all critical KPIs for top-level decision making.
Added tooltips to show customer trends and insights on hover.
Built drill-through & drill-down features (e.g., from Region → Country → Customer).
Applied conditional formatting and business-focused visuals to make reports intuitive.

🔹 5. **Performance Optimization**
Used DAX Studio to analyze query performance.
Optimized DAX measures (e.g., replacing row context with filter context where applicable).
Reduced dashboard refresh time for a smoother user experience.

🔹 6. **User Adoption**
Simplified navigation with bookmarks and buttons.
Added clear instructions and labels to improve accessibility for non-technical users.
Created a User Guide to explain dashboard usage.


**Key Insights & Recommendations
**
🔹Net Sales reached $823.85M in FY2021 → a 207% increase vs benchmark.
✅ Recommendation: Focus on sustaining this momentum by doubling down on high-performing regions & channels.

🔹Net Profit % dropped to -6.63% → high Marketing expenses need cost optimization.
✅ Recommendation: The marketing team should reassess campaigns, cut low-ROI spends, and redirect budget toward digital channels with better returns.

🔹LATAM region grew by ~58% → despite a small base ($3.16M), shows strong future potential.
✅ Recommendation: Increase investment in LATAM through partnerships, targeted promotions, and expanding distribution channels.

🔹Absolute Forecast Error spiked in FY2021 → indicating high fluctuations between under-forecasting & over-forecasting.
✅ Recommendation: Improve demand forecasting models by integrating historical sales + external factors (seasonality, promotions, competitor activity).

🔹AtliQ reached Top 5 in overall market share (5.8%), marking a major competitive milestone.
✅ Recommendation: Focus on retaining top customers and strengthening the supply chain to further climb the market ladder.

🔹~70% of revenue is generated through retailers like Amazon, Flipkart, Vivek, etc., emphasizing the importance of channel strategy.
✅ Recommendation: Diversify channels by boosting own e-store presence to reduce over-dependence on external retailers.


**Dashboards Preview**


Home Dashboard
<img width="1320" height="734" alt="image" src="https://github.com/user-attachments/assets/76b86b8e-0f41-4503-9b22-273bc860abb9" />


Finance Dashboard
<img width="1325" height="740" alt="image" src="https://github.com/user-attachments/assets/4d3fe86b-3fd5-497e-978d-91634c33ec63" />

Sales Dashboard
<img width="1322" height="742" alt="image" src="https://github.com/user-attachments/assets/b0263bcd-5ea4-4ed7-97b1-c5a4a4ce36b0" />

Marketing Dashboard
<img width="1323" height="740" alt="image" src="https://github.com/user-attachments/assets/913e77f6-7e16-4f89-98b5-b632c1398339" />

Supply Chain Dashboard
<img width="1325" height="738" alt="image" src="https://github.com/user-attachments/assets/5ac68edb-931e-4919-b8c6-d5e0d4e20ec0" />

Executive Dashboard
<img width="1320" height="739" alt="image" src="https://github.com/user-attachments/assets/fedc345c-306c-4531-90aa-10fc6469e444" />

**Tools & Technologies**
Power BI (Power Query, DAX, Data Modeling, Dashboards)
SQL + Excel (Data Sources)
DAX Studio (Performance Optimization)

**Skills Demonstrated**
ETL & Data Cleaning with Power Query
Data Modeling & Relationship Building
KPI Development with DAX
Dashboard Storytelling & Business Reporting
Performance Tuning & User Adoption

**Conclusion**
This project demonstrates how Power BI can transform raw data into actionable business insights, enabling companies like AtliQ Hardware to:

Identify cost-cutting opportunities
Discover new market growth potential
Provide executives with a single source of truth for decision-making
