📊 Power BI Sales Analytics Dashboard
An end-to-end Sales Analytics Dashboard built in Power BI, providing stakeholders a single pane of glass for monitoring revenue, profitability, geographic reach, product mix, and customer behaviour.

📁 File
SalesProject.pbix

🗂️ Data Model
Star schema with the following tables:
TableRoleKey FieldsDimProductProduct dimensionProductName, CategoryDimGeographyGeography dimensionCountry, RegionDimCustomerCustomer dimensionCustomerName, Gender, LoyaltyTierDatesDate dimensionYear, Quarter, MonthMeasure TableCentral KPI storeTotal Sales, Total Profit, YTD/QTD/MTD Sales, YoY Growth %, Total Orders, Avg Unit Price

📄 Report Pages
Page 1 — Sales Overview
Executive snapshot of overall business health.

Visuals: KPI Cards, Line Chart, Donut Chart, Gauge
Metrics: Total Sales, Total Profit, Total Orders, YTD Sales, YoY Growth %

Page 2 — Geographic Sales Analysis
Spatial breakdown of sales across regions and countries.

Visuals: Map Visual, Country Slicer
Metrics: Total Sales by Region, MTD Sales, Sales LY

Page 3 — Product Analysis
Category trends, profit mix, and product-level performance.

Visuals: KPI Visuals, Line Chart, Donut Chart, Cards, Table
Metrics: YTD/QTD/MTD Sales, Unique Products Sold, Total Quantity, Avg Unit Price, YoY Growth %

Page 4 — Customer Analysis
Demographics, loyalty segmentation, and CRM-level detail.

Visuals: Bar Chart, Scatter Chart, Table, Year Slicer
Metrics: Total Sales by Gender, Total Orders, LoyaltyTier, YoY Growth %


🛠️ Tools & Skills

Power BI Desktop
DAX — for time-intelligence and KPI measures (YTD, QTD, MTD, YoY)
Star Schema data modelling
Cross-filtering, drillthrough, and slicer-driven interactivity
