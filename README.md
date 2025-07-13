# 💼 Project Title:
**End-to-End Power BI Dashboard: House Market Analysis using Google BigQuery**

---

## 📝 Short Description:
This Power BI project demonstrates a complete BI workflow, starting from data extraction using Google BigQuery to building a dynamic and interactive dashboard for analyzing house market trends. It includes data transformation, advanced DAX measures, and visually appealing reports.

---

## 🎯 Purpose:
The goal of this project is to help real estate stakeholders understand market dynamics such as sales trends, regional performance, pricing patterns, and purchasing behavior. The interactive dashboard provides deep insights that can aid in data-driven decision-making.

---

## 🧰 Tech Stack / Tools Used:
- Power BI Desktop
- Google BigQuery
- Power Query Editor
- DAX (Data Analysis Expressions)
- Microsoft SQL Server (optional)

---

## 🔢 Data Source:
- **Source:** Google BigQuery Public Dataset
- **Type:** Real estate transactional data
- **Fields Included:**
  - Region, Area, City
  - Sales Type (e.g., auction, regular_sale)
  - Purchase Price, Offer Price
  - SQM (Size per square meter)
  - Date fields (Year, Quarter, Month)
  - House Type (Apartment, Villa, etc.)
  - Macroeconomic indicators (Interest, Inflation, Yield)

---

## 🧠 Key Features:
- Used Google BigQuery public datasets (100K+ rows) for real estate transactions
- Applied SQL transformations in BigQuery for efficient data shaping and preprocessing
- Designed a star schema model for scalable and structured data modeling
- Performed advanced calculations using DAX:
  - Year-over-Year (YOY) Growth
  - Last Twelve Months (LTM) Sales
  - TOTALYTD sales aggregation
- Developed dynamic KPI cards (Units Sold, Total Sales, Price Change %)
- Created visual comparisons like:
  - Median Sales Price Change by Region
  - Offer Price vs Purchase Price (Scatter)
  - Sales by Region (Waterfall)
  - SQM Ratio by Sales Type
- Implemented advanced visuals:
  - Key Influencer visual for understanding purchase behavior
  - Clustered bar, donut, and pie charts
- Enabled interactive filtering by Region, Area, City, Sales Type, and House Type
- Published the report to Power BI Service with scheduled auto-refresh


---

## 📊 Example Visualizations:
- Median Sales Price Change by Region
- YOY Sales Growth by Sales Type
- Sales by Region (Waterfall & Bar Charts)
- Donut Chart showing average prices
- Offer Price vs Purchase Price (Scatter Plot)
- Clustered Bar Chart by House Type
- Key Influencer Analysis
- House Type Analysis with Filters

---

## ❓ Business Questions Answered:
- Which region has shown the highest/lowest change in sales price?
- How do different sales types perform year-over-year?
- What's the average price per square meter by region?
- Are offer prices generally higher than purchase prices?
- Which house types yield the highest ROI?
- Which regions generate the most sales revenue?

---

## 💡 Business Impact & Insights:
- Identify underperforming or overpriced markets for strategic investment
- Track macroeconomic trends affecting housing demand and pricing
- Help real estate developers prioritize high-demand regions and house types
- Optimize marketing and pricing strategy using data-driven visual cues

---

## 🖼️ Screenshots:

- **Dashboard Overview**  
  ![House-Market-Analysis Dashboard 1](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%201.png)
  ![House-Market-AnalysisDashboard 2](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%202.png)
  ![House-Market-Analysis Dashboard 3](https://github.com/AACHAL2303PATIL/House-Market-Analysis-using-Google-BigQuery/blob/main/House%20Dashboard%203.png)

---

## 🚀 How to Use:
1. Connect to the dataset via Google BigQuery (or import CSV)
2. Perform data cleaning using Power Query Editor
3. Apply DAX formulas for metrics like YOY growth, totals, medians
4. Build visuals using charts, slicers, and KPIs
5. Publish report to Power BI Service for web access or sharing

---

## 📂 Dataset:
🔗 [Click here to access the dataset](https://drive.google.com/file/d/1PpuWPloKOtTau5yG7QkXP2fuoDpQdXK4/view)

