## 📂 Project Overview:
This project aims to transform raw transactional data into actionable insights using Microsoft Excel. It highlights regional performance, quantity sold, and profitability using data modeling, aggregation, and visualization techniques.

## 🧠 Tools & Features Used:
- Microsoft Excel
- Power Query
- Power Pivot
- PivotTable Analyze
- Pivot Tables & Pivot Charts
- Slicers
- Gradient Design & Color Palette Customization
- Excel Formulas (SUM, AVERAGE, MAX, MIN)
- Sheet-level cell referencing

## 📊 Skills Demonstrated:
- Advanced Excel functionality
- Data wrangling and transformation
- Business KPI design and interpretation
- Dashboard storytelling and formatting
- Dynamic linkage between sheets and visuals

## 📐 Step-by-Step Process:
🔄 1. Data Cleaning (Power Query)
- Converted the raw dataset into a table using **Insert → Table → From Table/Range**
- Entered **Power Query Editor** to:
  - Remove blank/null values
  - Rename columns for clarity
  - Change data types (e.g., Date, Integer, Currency, Percent)
- Loaded the cleaned data into the **Data Model**

🧩 2. Data Modeling (Power Pivot)
- Opened **Power Pivot → Manage** to view the data model
- Managed relationships and calculated KPIs using formulas in a new sheet (`Analysis`)
- Loaded data from the model to create Pivot Tables

📊 3. KPI Calculation (Analysis Sheet)
Used Excel formulas to calculate key performance indicators:

- `=SUM([REVENUE])` → **Total Sales**
- `=SUM([QTY SOLD])` → **Total Quantity Sold**
- `=SUM([REVENUE]) - SUM([UNIT PRICE])` → **Total Profit**
- `=SUM([PROFIT MARGIN])` → **Total Profit Margin**
- `=AVERAGE([PROFIT MARGIN])` → **Average Profit Margin**
- `=MAX([PROFIT MARGIN])` → **Maximum Profit Margin**
- `=MIN([PROFIT MARGIN])` → **Minimum Profit Margin**

These values are displayed in the `Analysis` sheet and linked to the dashboard using cell references.

📈 4. Dashboard Design
- Created Pivot Tables using the **Data Model**
- Converted Pivot Tables into interactive Pivot Charts (Bar, Line, Pie)
- Designed the dashboard with:
  - Gradient background fills
  - Consistent color palette
  - Visual slicers for filtering
- Pulled KPI values to the dashboard using direct cell references such as:
  - `=ANALYSIS!B4` → Total Sales
  - `=ANALYSIS!D4` → Total Profit
  - `=ANALYSIS!G4` → Maximum Profit Margin
  - `=ANALYSIS!H4` → Minimum Profit Margin

## 📁 Project Structure:
📦 MULTINATIONAL_COFFEESHOP_SALES/
│
├── 📁 DATA/
│   └── Globalsales_Coffeeshop_Dashboard.xlsx 
│   └── Raw_Data.xlsx
│
├── 📁 VISUALS/               
│   ├── Dashboard_globalsales.png
│   ├── PivotTable.png
│   └── PowerPivot.png
│
├── 📄 README.md                             
