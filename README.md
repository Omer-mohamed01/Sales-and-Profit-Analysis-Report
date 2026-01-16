<img width="2147" height="67" alt="image" src="https://github.com/user-attachments/assets/a7e25bbb-a380-40c4-b0af-f98a6b921ad3" /># 🛒 Superstore Sales & Profit Analysis
Designed to transform the Superstore dataset into actionable business intelligence. It provides an end-to-end view of organizational health, moving from high-level executive KPIs to granular customer and product-level insights.

## Data Used
<a href="https://www.kaggle.com/datasets/vivek468/superstore-dataset-final">Superstore Dataset</a>
</br>
Used under a public data license for educational purposes.

## Dasboard
<a href="https://app.powerbi.com/groups/98373b82-8bf8-4949-a965-40a9fb1cd6f3/list?experience=power-bi">Superstore Sales & Profit Analysis</a>
</br>

## 📊 Project Overview
The goal of this project is to analyze Superstore sales data to identify key drivers of profit and loss across products, regions, and time periods.
By uncovering these insights, the project aims to help guide data-driven marketing and operational strategies to increase profitability.

## 🧩 Business Task
Increase profit by understanding which products, regions, and time periods drive the most and least sales and what are the potential areas for marketing focus to boost sales and profit.

## 🧰 Tools Used
Excel – Data cleaning and preprocessing.
</br>
Power BI – Data modeling, DAX measures, dashboards.
</br>
PowerPoint → Final presentation of insights and recommendations.

## 🧹 Data Cleaning
Removed duplicates and handled missing values.
</br>
Removed rows with missing or invalid values (e.g., null times, negative sales)
</br>
Checked for missing values in key columns (Sales, Profit, Region, Dates) and handled them appropriately.
</br>
Standardized date formats (Order Date, Ship Date) to DD/MM/YYYY.
</br>
Cleaned currency symbols and spaces in Sales and Profit columns for numerical calculations.
</br>
Validated relationships between fields (e.g., no negative sales or incorrect dates). 
</br>
Ensured consistent text formatting (e.g., product names, region names).
</br>
Created new calculated columns:
</br>
-Ship Days : Difference between Ship Date and Order Date
</br>
-Shipping Speed : Slow, Average, Fast on Ship Days
</br>
-Year, Quarter, Month extracted from Order Date
</br>
-Avg Profit Margin = Profit / Sales
</br>
-Sales Category = Profitable / Loss based on Profit value

## 📈 Key Insights
Category Profitability Drain: While the overall business is healthy, the Furniture category is a significant "leaky bucket," yielding a razor-thin 2.49% margin.
</br>
Top-Tier Customer Value: A elite group of "Champion" customers, including Tamara Chand and Raymond Buch, generate highly profitable orders with margins exceeding 45%.
</br>
Logistics Bottlenecks: Analysis of Avg Ship Days identifies specific regions where shipping speed is currently a bottleneck, potentially impacting customer retention.
</br>
![](https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/fa9f1a6b377e3a175aaec7a01d13a3c3a05821bb/Charts/Average%20Profit%20Margin%20Category.png)
</br>
![](https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/fa9f1a6b377e3a175aaec7a01d13a3c3a05821bb/Charts/Monthy%20Profit%20Trend.png)

## 💡 Recommendations
Product Bundling Strategy
</br>
VIP Loyalty Program.
</br>
Regional Logistics Optimization.


## 🧠 Outcome
This analysis provides data-driven insights for Superstore marketing strategy, emphasizing what are the potential areas for marketing focus to boost sales and profit.
</br>
The project translates raw healthcare data into practical insights that support improved operational efficiency and patient experience.
---


## 🗂️ Project Structure


Superstore Sales & Profit Analysis
</br>
README.md
</br>
LICENSE
</br>
├── Data |
    └──<a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Data%20Source/Sample%20-%20Superstore.csv">Data Source.csv</a>
    </br>
├── Link |
    └──<a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Data%20Source/Data%20Source%20Link.txt">Data Source Link.txt</a>
</br>
├── Business Task |
    └──<a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/tree/ee78b296dc7fbe8cd9d4b3a30fa079dbd740aa29/Business%20Task">Business Task.txt</a>
</br>
├── Excel |
  └──<a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Data%20Cleaning/Superstore.xlsx">Data Cleaning.xlsx</a>
</br>
├── Presentation |
   └── <a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Document/Superstore%20Sales%20%26%20Profit%20Analysis%20Presentation.pdf">Superstore Sales & Profit Analysis.pdf</a>
</br>
├── Charts |
   └── <a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/tree/5ae38ade9492e5706426ff03e16b3ee2041e10da/Charts">Charts.png</a>

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---
