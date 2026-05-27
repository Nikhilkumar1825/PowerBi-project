


# Ecommerce Sales Dashboard


## Problem Statement
This dashboard is designed to help the Nikku Ecommerce business gain a clear, data-driven understanding of its sales performance. The business needed a single view to monitor key metrics — total revenue, profit, quantity sold, and average order value — broken down by state, product category, customer, and payment mode.

A key challenge was identifying which months generate losses (negative profit), which sub-categories are most profitable, and which states and customers drive the most revenue — so management can make informed decisions on inventory, promotions, and regional strategies.


### Steps followed 



- Step 1 : Load data into Power BI Desktop

  Import the ecommerce dataset (CSV format) into Power BI Desktop to begin the data modelling and visualization process.
- Step 2 : Open Power Query Editor & enable data preview

  In the View tab under Data Preview, enable "Column Distribution", "Column Quality", and "Column Profile" to inspect data health before building visuals.
- Step 3 : Set column profiling to entire dataset
 
  By default, Power BI profiles only the first 1,000 rows. Change the setting to profile based on the entire dataset for accurate quality insights.

- Step 4 :Handle null values in the Profit column

  Null/blank values were found in the Profit column. Since these represent months with losses (negative profit), they were retained and handled carefully in calculations to avoid skewing results.
- Step 5 : Select a report theme

  In the Report view, under the View tab, apply a dark/space theme (deep navy/purple gradient background) to give the dashboard a professional, modern aesthetic consistent with the brand. 
- Step 6 : Add KPI card visuals

  Insert four card visuals representing Sum of Amount (438K), Sum of Profit (37K), Sum of Quantity (5,615), and Sum of AOV (121K) for an at-a-glance performance summary.
- Step 7 : Add quarter & category slicers (filters)

  Add button slicers for Qtr 1, Qtr 2, Qtr 3, and Qtr 4, plus a dropdown slicer for category (All / Clothing / Electronics / Furniture) to enable dynamic filtering across all visuals.
- Step 8 : Create "Sum of Amount by State" bar chart

  Build a horizontal bar chart showing revenue by state — Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi — to identify top-performing regions.
- Step 9 : Create "Sum of Quantity by Category" donut chart

  Build a donut chart breaking down quantity sold by category: Clothing (63%), Electronics (21%), and Furniture (17%) — highlighting which product lines move the most volume.
- Step 10 : Create "Profit by Month" column chart

  Build a column chart showing monthly profit across all 12 months. Positive months (Jan–May, Nov) display in blue; loss-making months (Jun–Oct, Dec) display in orange to visually flag underperformance. 
- Step 11 : Create "Sum of Amount by CustomerName" bar chart

  Build a bar chart showing revenue by top customers — Harivansh, Madhav, Madan Mohan, and Shiva — to identify high-value buyers for targeted retention strategies.



- Step 12 : Create "Sum of Quantity by Payment Mode" donut chart

  Build a donut chart showing payment method distribution: COD (44%), UPI (21%), Debit Card (13%), Credit Card (12%), and others — helping understand customer payment preferences.
- Step 13 : Create "Sum of Profit by Sub-Category" bar chart

  Build a horizontal bar chart showing profit by sub-category — Printers (highest), Bookcases, Saree, Accessories, and Tables — to identify which product lines are most profitable.
- Step 14 : Add dashboard title and branding

  Insert a text box with the title "NIKKU ECOMMERCE SALES DASHBOARD" styled with a prominent border and contrasting colors to anchor the report's identity at the top.





 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](<img width="1344" height="737" alt="Image" src="https://github.com/user-attachments/assets/cdb79a4a-c8f2-4098-8272-194b6ea4ba98" />)



