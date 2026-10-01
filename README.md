# 📊 Super Store Sales Dashboard

An interactive **Power BI Sales Performance Dashboard** designed to analyze sales performance across products, categories, customer segments, shipping modes, regions, and time.

The project transforms sales transaction data into meaningful business insights using **Power BI visualizations, KPI cards, interactive filters, geographic analysis, trend analysis, and sales forecasting**.

---

## 🎯 Project Objective

The main objective of this project is to build an interactive sales analytics dashboard that helps users understand overall business performance and identify important sales trends.

The dashboard provides insights into:

* Overall sales performance
* Product and category performance
* Customer segment contribution
* Shipping mode analysis
* Regional sales performance
* Sales and profit trends over time
* Quantity performance
* Average delivery performance
* Future sales forecasting

The project demonstrates how **Power BI can transform raw sales data into an interactive business intelligence dashboard**.

---

## ✨ Key Features

### 💰 Sales Performance Analysis

The dashboard tracks overall sales using KPI cards and visualizations.

Key metrics include:

* Total Sales
* Total Quantity
* Average Delivery
* Sales by different business dimensions

These KPIs provide a quick overview of the overall sales performance.

---

### 📦 Category Analysis

Sales performance is analyzed across different product categories.

The dashboard uses a **clustered bar chart** to compare sales between categories.

This helps identify:

* High-performing categories
* Low-performing categories
* Differences in sales contribution between categories

---

### 🛍️ Product Analysis

The dashboard includes product-level sales analysis.

A **clustered bar chart** is used to visualize sales across products.

This helps users understand which products contribute more significantly to overall sales.

---

### 👥 Customer Segment Analysis

A **donut chart** analyzes sales based on customer segments.

This allows users to compare the contribution of different customer groups to total sales.

---

### 🚚 Shipping Mode Analysis

The dashboard analyzes sales according to different shipping modes.

Shipping performance is visualized using:

* Clustered bar chart
* Donut chart

This provides a clear view of how sales are distributed across shipping methods.

---

### 🌎 Regional Analysis

The dashboard includes an interactive **map visualization** showing sales and profit by region.

A **Region slicer** is also provided so users can filter the dashboard according to a selected region.

This allows users to explore regional performance interactively.

---

### 📈 Time-Based Sales Analysis

The dashboard contains time-based visualizations for analyzing sales performance over time.

A stacked area chart is used to visualize:

* Sales by month
* Sales by day
* Sales by year

This makes it easier to identify changes and trends in sales performance.

---

### 💹 Profit Trend Analysis

The dashboard also analyzes profit over time.

The profit trend visualization uses the order date hierarchy to examine:

* Monthly profit
* Daily profit
* Yearly profit

This helps users understand how profitability changes over time.

---

### 🔮 Sales Forecasting

A separate report page provides **sales trend analysis and forecasting**.

The forecast visualization uses historical sales based on `Order_Date` and applies Power BI's forecasting capability to estimate future sales.

The forecast configuration in the report uses:

* Forecasting algorithm
* 95% confidence level
* Future forecast period

Forecasting can help businesses understand potential future sales trends and support planning activities.

> Forecast values are analytical estimates based on historical data and should not be treated as guaranteed future results.

---

## 📊 Dashboard Visualizations

The main dashboard contains the following visualizations:

| Visualization      | Analysis                   |
| ------------------ | -------------------------- |
| KPI Card           | Total Sales                |
| KPI Card           | Total Quantity             |
| KPI Card           | Average Delivery           |
| Donut Chart        | Sales by Segment           |
| Bar Chart          | Sales by Category          |
| Bar Chart          | Sales by Product           |
| Bar Chart          | Sales by Ship Mode         |
| Donut Chart        | Sales by Ship Mode         |
| Stacked Area Chart | Sales over Time            |
| Stacked Area Chart | Profit over Time           |
| Map                | Sales and Profit by Region |
| Slicer             | Region Filter              |

---

## 📄 Report Pages

### Page 1 — Super Store Sales Dashboard

The main dashboard provides a complete overview of sales performance.

It includes:

* Sales KPI
* Quantity KPI
* Average Delivery KPI
* Segment analysis
* Category analysis
* Product analysis
* Shipping mode analysis
* Sales trend
* Profit trend
* Regional map
* Region slicer

The page is designed as a single interactive dashboard for quick business analysis.

---

### Page 2 — Sales Forecast

The second report page focuses on sales trends and forecasting.

It contains line charts based on:

* Order Date
* Total Sales

One of the visualizations includes a Power BI forecast to estimate future sales based on historical sales patterns.

---

## 🗂️ Data Model

The dashboard is built around the following primary dataset:

**`Sales_Clean_Data`**

Important fields used in the dashboard include:

* `Order_Date`
* `Sales`
* `Profit`
* `Quantity`
* `AvgDelivery`
* `Segment`
* `Category`
* `Product`
* `Ship_Mode`
* `Region`

These fields are used to create the dashboard's KPIs, charts, map, filters, and forecasting analysis.

---

## 🔄 Data Flow

```text
Raw Sales Data
       ↓
Data Cleaning
       ↓
Sales_Clean_Data
       ↓
Data Analysis
       ↓
KPI Calculations
       ↓
Power BI Visualizations
       ↓
Interactive Dashboard
       ↓
Trend Analysis
       ↓
Sales Forecast
       ↓
Business Insights
```

---

## 🎛️ Interactive Features

The dashboard includes interactive Power BI features such as:

### Region Slicer

Users can select a region to filter the dashboard.

This allows users to investigate sales performance for individual regions.

### Cross-Visual Interaction

Selecting information from one visualization can affect other dashboard visuals, making it easier to explore relationships between different sales dimensions.

### Date Hierarchy

The dashboard uses the `Order_Date` field with date hierarchy levels such as:

* Year
* Month
* Day

This allows sales and profit trends to be examined at different time levels.

---

## 📌 Key Business Questions

The dashboard can help answer questions such as:

* What is the total sales performance?
* How many products or units were sold?
* Which product categories generate the most sales?
* Which products contribute significantly to sales?
* Which customer segment contributes the most sales?
* Which shipping mode generates the most sales?
* How are sales distributed across regions?
* How does profit change over time?
* How does sales performance change over time?
* What are the historical sales trends?
* What does the sales forecast indicate about future performance?

---

## 💡 Business Insights

The dashboard can support business decisions by helping organizations:

* Identify high-performing products
* Compare category performance
* Understand customer segment contribution
* Monitor regional sales
* Analyze shipping preferences
* Track sales trends
* Monitor profit trends
* Evaluate quantity performance
* Examine delivery performance
* Use historical trends for sales forecasting

These insights can support **sales planning, product management, regional analysis, and business performance monitoring**.

---

## 🧮 Power BI Techniques Used

This project demonstrates practical use of:

* Power BI
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Cards
* Donut Charts
* Clustered Bar Charts
* Stacked Area Charts
* Maps
* Slicers
* Date Hierarchies
* Aggregations
* Cross-filtering
* Time-Series Analysis
* Forecasting
* Dashboard Design
* Business Intelligence

---

## 📈 Forecasting

The project includes a dedicated sales forecasting page.

The forecast is generated from historical sales data using `Order_Date` and `Sales`.

The configured forecast uses a **95% confidence level**, providing an estimated future sales trend together with uncertainty around the forecast.

Forecasting can be useful for:

* Sales planning
* Inventory planning
* Revenue estimation
* Business forecasting
* Identifying potential future trends

---

## 🛠️ Tools & Technologies

**Primary Tool:** Microsoft Power BI

**Techniques:**

`Power BI` • `Data Cleaning` • `Data Modeling` • `KPI Cards` • `Charts` • `Map Visualization` • `Slicers` • `Date Hierarchy` • `Forecasting` • `Dashboard Design`

---

## 📁 Repository Contents

```text
Super-Store-Sales-Dashboard/
│
├── sales performance dashboard 3.pbix
└── README.md
```

---

## 🎓 Project Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Analytics
* Business Intelligence
* Microsoft Power BI
* Data Visualization
* Dashboard Development
* Sales Analysis
* KPI Development
* Time-Series Analysis
* Geographic Analysis
* Forecasting
* Business Decision-Making

---

## ⚠️ Limitations

* The dashboard depends on the quality and completeness of the underlying sales dataset.
* Forecast values are estimates based on historical sales patterns.
* Forecast results may change when additional or updated sales data is introduced.
* Dashboard results should be interpreted according to the available dataset and selected filters.
* The project is intended primarily for academic and demonstration purposes.

---

## 🔮 Future Improvements

Possible future enhancements include:

* Additional KPI measures
* Customer-level analysis
* Profit margin analysis
* Year-over-year sales comparison
* Monthly and yearly growth calculations
* More advanced forecasting
* Customer segmentation
* Top and bottom product analysis
* Dynamic tooltips
* Additional slicers
* Drill-through pages
* Automated data refresh
* Power BI Service deployment

---

## 📌 Project Type

**Academic / Data Analytics / Business Intelligence Project**

**Domain:** Sales & Business Analytics

**Tool:** Microsoft Power BI

**Dashboard:** Super Store Sales Dashboard

---

## 👩‍💻 Author

**Sudipa Roy**

BCA Student | Data Analytics with AI

---

## ⭐ Acknowledgement

This project was developed as an academic/practical demonstration of using **Microsoft Power BI for sales analysis, business intelligence, data visualization, interactive dashboard development, and forecasting**.

The project demonstrates how raw sales data can be transformed into meaningful visual insights to support data-driven business analysis.
