# Global Profit Analysis Dashboard – Power BI

**Project Overview**
This Power BI project analyzes global company performance using a dataset structured across three tables. The dashboard provides key financial insights such as profit distribution by continent, product type, and category, with dynamic filtering and calculated metrics powered by DAX.

**Data Model & Transformations**
- Tables Used:
- Sales Data – Contains raw transactional data
- Product Info – Includes product type and category
- Metrics Table – Contains calculated KPIs using DAX
- Power Query Transformations:
- Extracted Quarter and Year from date fields using delimiter logic
- Translated country and region names into English for consistency
- Established relationships between tables for seamless filtering

**DAX Calculations**
The third table includes custom metrics created with DAX, such as:
- Total Profit
- Profit Margin
- Income and Expenses by Region
- Year-over-Year comparisons
These measures drive the dynamic visuals and KPI cards in the dashboard.

**Dashboard Features**
- KPI Card: Displays key metrics like total income, expenses, profit, and margin
- Pie Chart: Shows profit distribution by continent
- Filters:
- Year
- Product Type
- Product Category
- Clean layout with intuitive navigation and responsive visuals

**Tools Used**
- Power BI Desktop
- Power Query for ETL
- DAX for calculated metrics
- Excel (source data)

**Dashboard Preview**
(Include a screenshot in the assets/ folder and link it here)
![Dashboard Overview](assets/dashboard_view.png)


Let me know if you'd like a Spanish version or want to add a section explaining specific DAX formulas for recruiters or hiring managers.
