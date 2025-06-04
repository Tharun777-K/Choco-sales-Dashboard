# Sweet Insights: A Power BI Dashboard for Chocolate Factory Operations
This Power BI dashboard was developed to monitor and analyze the key performance indicators (KPIs) of a chocolate manufacturing unit.

## Project Objective
This Power BI dashboard was developed to monitor and analyze the key performance indicators (KPIs) of a chocolate manufacturing unit. The dashboard provides interactive visualizations of production output, raw material usage, sales trends, inventory status, and quality control metrics. It aims to help factory managers and stakeholders make data-driven decisions to improve operational efficiency, reduce waste, and enhance customer satisfaction.

## Dataset Used
- <a href="https://github.com/Tharun777-K/Choco-sales-Dashboard/blob/main/sample-chocolate-shipments-data-all-Apr-2025.xlsx">Data Set</a>

## Questions(KPI)
- Compare the sales and orders using single chart.
- Which month got the highest sales and orders?
- List top 10 states contributingto the sales?
- What are the total sales by product category (e.g., dark, milk, white chocolate)?
- What is the profit margin for each chocolate product type?
- Which regions or distributors are generating the highest/lowest revenue?

- Dashboard Interaction <a href="https://github.com/Tharun777-K/Choco-sales-Dashboard/blob/main/powerBI_demo1.pbix">View Dashboard</a>
## Project Workflow: Chocolate Factory Power BI Dashboard
✅ 1. Understanding Business Requirements
- Met with stakeholders (factory managers, sales team, quality control, etc.) to gather key metrics they wanted to track.
- Identified the core areas: Production, Inventory, Quality, Sales, and Operations.
- Finalized list of KPIs (e.g., production output, defect rate, material wastage, stock levels).
  
📥2.Collected data from multiple sources:
- ERP system (production logs, inventory data)
- Sales database or Excel files
- Quality control sheets (manual or digital)
- External sources (like market prices or customer feedback if available)
- Exported raw data in formats such as CSV, Excel, or connected directly to SQL/Access databases.

🧹 3. Data Cleaning & Preprocessing
- - Cleaned data using Power Query in Power BI:
- Removed duplicate rows
- Handled missing or null values
- Standardized date formats and measurement units (e.g., kg vs g)
- Merged multiple tables using keys like Batch ID, Product ID
- Created calculated columns (e.g., Yield %, Defect Rate)

🔗 4. Data Modeling
- Defined relationships between tables (one-to-many, many-to-one)
  Example: One Product ➝ Many Sales
- Created a Star Schema structure for better performance:
  Fact Table: Production, Sales, Inventory
- Dimension Tables: Product, Time, Region, Machine
- Defined measures using DAX (Data Analysis Expressions):
  Total Output = SUM(Production[Quantity])
  
  Defect Rate = SUM(DefectQty) / SUM(TotalProduced)

📊 5. Dashboard Design in Power BI
Created multiple report pages:

- Production Overview
- Quality Control
Inventory & Stock
- Sales Analysis

Used visuals such as:
- Bar/Column Charts for trends
- Pie Charts for product category distribution
- Line Graphs for performance over time
- KPI Cards for key metrics
- Slicers for filtering by Date, Region, Product Type
- Applied color themes (e.g., chocolate tones) for aesthetics and consistency.

📤 7. Deployment & Sharing
- Published the dashboard to Power BI Service
- Set up scheduled data refresh (daily or weekly)
- Shared access with stakeholders and collected feedback
- Made iterative improvements based on user feedback

📈 8. Monitoring & Updates
- Tracked dashboard usage and updated reports as new data sources or KPIs were introduced.
- Maintained documentation for future enhancements or team handover.


## Dashboard
![Dashboard_Image](https://github.com/user-attachments/assets/11298f75-728e-41cd-8eba-974e37383a38)

## ✅ Final Conclusion
The Power BI dashboard developed for the chocolate factory successfully transformed raw, scattered data into meaningful and actionable insights. By integrating data from production, inventory, sales, and quality control systems, the dashboard enables factory managers and stakeholders to monitor performance in real-time, identify inefficiencies, and make data-driven decisions.
