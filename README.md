# 🚗 Car Sales Dashboard – Power BI Project

This repository contains a dynamic and interactive **Car Sales Dashboard** built using **Power BI**. The dashboard is designed to help our car dealership track, analyze, and optimize sales performance across multiple dimensions including time, region, car attributes, and dealerships.

---

## 🎯 Objective

The main objective of this project is to **visualize key sales metrics** and **derive actionable insights** to support data-driven decision-making. The dashboard presents **real-time KPIs**, sales trends, and geographical analysis to help monitor performance and identify growth opportunities.

---

## 🧩 Problem Statements & Requirements

### 📌 Problem Statement 1: KPI Requirements

The dashboard includes the following **key performance indicators (KPIs)**:

#### 🔹 Sales Overview
- **Year-to-Date (YTD) Total Sales**
- **Month-to-Date (MTD) Total Sales**
- **Year-over-Year (YOY) Growth** in Total Sales
- **Difference** between YTD and Previous Year-to-Date (PTYD) Sales

#### 🔹 Average Price Analysis
- **YTD Average Price**
- **MTD Average Price**
- **YOY Growth** in Average Price
- **Difference** between YTD and PTYD Average Price

#### 🔹 Cars Sold Metrics
- **YTD Cars Sold**
- **MTD Cars Sold**
- **YOY Growth** in Cars Sold
- **Difference** between YTD and PTYD Cars Sold

---

### 📌 Problem Statement 2: Charts & Visualizations

To enhance interpretability and engagement, the dashboard includes the following visual elements:

1. **📈 YTD Sales Weekly Trend**
   - A **line chart** showing weekly sales performance.
   - **X-axis:** Weeks | **Y-axis:** Total Sales

2. **🥧 YTD Total Sales by Body Style**
   - A **pie chart** visualizing the sales distribution across various car body styles.

3. **🎨 YTD Total Sales by Color**
   - A **pie chart** displaying the sales contribution of different car colors.

4. **🗺 YTD Cars Sold by Dealer Region**
   - A **map chart** showing the geographical distribution of car sales by dealer region.

5. **📊 Company-Wise Sales Trend (Grid)**
   - A **tabular grid** presenting:
     - Company Names
     - YTD Sales figures

---

## 📁 Repository Structure

```
🚗 CarSalesDashboard/
├── PowerBI_Dashboard.pbix        # Main Power BI file
├── data/
│   └── Car_Sales_Data.csv        # Source dataset
├── assets/
│   └── screenshots/              # Dashboard screenshots (optional)
├── README.md                     # Project documentation
└── documentation/
    └── KPI_Definitions.md        # Definitions and calculations for each KPI
```

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Data Modeling (DAX, Power Query)**
- **Visualizations (Charts, Maps, Tables)**
- **CSV/Excel data sources**

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Load the dataset (`Car_Sales_Data.csv`) if not already embedded.
4. Explore the dashboard using filters, slicers, and visual elements.

---

## 📌 Future Enhancements

- Drill-down functionality for dealers and individual models
- Advanced forecasting using historical sales data
- Integration with live databases or APIs for real-time updates

---

## 🙌 Contributions

Contributions and feedback are welcome! Please open an issue or submit a pull request for suggestions or enhancements.

---
