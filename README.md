**Nigeria Car Market Analysis — Excel Dashboard**

📌 Project Description
An end-to-end data analysis project built entirely in Microsoft Excel, exploring the Nigerian car market across 3,722 listed vehicles. The project covers everything from raw data cleaning to an interactive two-page dashboard, uncovering pricing patterns, buyer preferences, and market distribution insights.

🎯 Objectives

Analyze car distribution across price bands, models, colors, and cities
Identify the most preferred fuel types, gear types, and car conditions
Understand how car age, brand, engine type, and condition influence pricing
Compare average prices across Nigeria's top registered cities
Surface actionable insights for buyers, sellers, and market analysts


📁 Project Structure
nigeria-car-market-analysis/
│
├── Car_Sales.xlsm                  # Main Excel workbook (macro-enabled)
├── README.md                       # Project documentation
└── screenshots/
    ├── page1_market_overview.png
    └── page2_value_performance.png

🗂️ Workbook Structure
SheetPurposecar_pricesRaw dataset — all vehicle listings with 20 columnsWorking SheetData cleaning, transformation, and helper columnsOverview PivotPivotTables powering Page 1 visualsBreakdown PivotPivotTables powering Page 2 visualsDashboardPage 1 — Market & Performance OverviewDashboard 2Page 2 — Value & Performance Analysis

📊 Dataset Columns
ColumnDescriptioncar_idUnique vehicle identifierpriceListed price in Nairafuel_typePetrol / Diesel / Hybridgear_typeAutomatic / Manual / CVTMakeCar manufacturer (e.g. Toyota, Mercedes-Benz)ModelSpecific model (e.g. Camry, M Class)Year of manufactureProduction yearColourBody colorConditionNigerian Used / Foreign Used / Brand NewMileageDistance covered in kmEngine SizeEngine capacity in ccSelling ConditionRegistered / Imported / Brand NewBought ConditionOriginal purchase conditioncarCar body type (SUV, Sedan, Truck, etc.)TrimSpecific trim/variantDrivetrainFront Wheel / Rear Wheel / All WheelSeatsNumber of seatsNumber of CylindersEngine cylindersHorse PowerEngine horsepowerRegistered CityCity of registration

⚙️ Process
1. Data Cleaning (Working Sheet)

Removed duplicate entries using Remove Duplicates
Standardized inconsistent city names (e.g. "LAGOS", "Lagos", "lagos" → "Lagos")
Handled blank cells in Mileage, Engine Size, and Registered City columns
Corrected data types for price and mileage columns
Applied custom number formatting for currency (₦ with M/K suffixes) and mileage

2. Feature Engineering (Working Sheet)

Created Price Band grouping column: Economy / Mid-Range / Upper-Class / Luxury
Created Car Age bracket column: 4–10 / 11–17 / 18–24 / 25–31 / 32–38 / 39+
Standardized selling condition and car type fields for consistent grouping

3. Analysis (PivotTables)

Built PivotTables to summarize counts and averages by model, color, city, fuel type, gear type, condition, brand, car type, and engine type
Used AVERAGEIF, COUNTIF, and SUMIF formulas for KPI calculations
Calculated percentage shares for fuel type and gear type distributions

4. Dashboard Design

Built two fully interactive dashboards using PivotCharts and slicers
Applied a dark theme for a professional, modern look
Used orange accent colors for KPI highlights and key callouts
Added insight callout boxes summarizing key findings on each page
Configured slicers for filtering by Manufacturing Year, Registered City, Selling Condition, and Price Band


📊 Dashboard Pages
Page 1 — Market & Performance Overview
KPIs: Total Listed Vehicles (3,722) | Avg. Price (₦4.51M) | Avg. Mileage (195/km) | Top Selling Model — Camry (548) | Avg. Engine Capacity (10.9L)
Visuals: Distribution by Price Band · Top 5 Car Colors · Distribution by Model · Fuel Type (Donut) · Gear Type (Donut) · Car Conditions

Page 2 — Value & Performance Analysis
Visuals: Avg. Price by Car Age · Top 10 Cities by Avg. Price · Avg. Price by Car Type · Price by Engine Type · Top 10 Brand Prices · Avg. Price by Condition

💡 Key Insights

Mid-range cars dominate with 1,891 units listed
Camry is the top-selling model with 548 units
98.60% of buyers prefer petrol vehicles
93.71% prefer automatic transmission
Black is the most preferred color with 1,009 listings
4–10 year old vehicles have the highest average price at ₦14.45M
Bentley leads brand pricing at ₦24.15M average
Asaba has the highest city average at ₦6.71M
Convertibles are the priciest car type at ₦13.56M average
Imported cars dominate by selling condition with 1,939 units


✅ Recommendations

For sellers: Stock mid-range petrol automatic vehicles — highest demand segment
For buyers: Target 18–24 year old vehicles for the best value at ₦1.89M average
For dealerships in Asaba and FCT: Premium pricing strategies are viable given higher city averages
For importers: Black and gray Camrys and Corollas consistently move fastest
For market analysts: Monitor convertible and performance engine segments as luxury demand 


🛠️ Tools Used

Microsoft Excel — Data cleaning, PivotTables, PivotCharts, Slicers, Dashboard design


👩🏽‍💻 Author
Precious Ogba Oluchi
Data Analyst | Microsoft Certified: Power BI Data Analyst Associate (PL-300)
www.linkedin.com/in/precious-ogba-a40902230


🛠️ Tools Used

Microsoft Excel — Data cleaning, PivotTables, PivotCharts, Slicers, Dashboard design
