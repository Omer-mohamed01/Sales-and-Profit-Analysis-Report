# 🛒 Superstore Sales & Profit Analysis
Sales and Profit Analysis of Superstore Dataset using Excel — A data analysis project focused on identifying key drivers of profit across products, regions, and time periods. Includes data cleaning, trend analysis, and insights to guide marketing and business decisions.

## Data Used
<a href="https://www.kaggle.com/datasets/vivek468/superstore-dataset-final">Superstore Dataset</a>
</br>
Used under a public data license for educational purposes.

## 📊 Project Overview
The goal of this project is to analyze Superstore sales data to identify key drivers of profit and loss across products, regions, and time periods.
By uncovering these insights, the project aims to help guide data-driven marketing and operational strategies to increase profitability.

## 🧩 Business Task
Increase profit by understanding which products, regions, and time periods drive the most and least sales and what are the potential areas for marketing focus to boost sales and profit.

## 🧰 Tools Used
Excel → Data cleaning, merging, and transformation
</br>
PivotTables & Charts → Statistical summaries and visualization
</br>
PowerPoint → Final presentation of insights and recommendations

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
Top products and technology category deliver the highest profit margins.
</br>
Certain regions and months drive the majority of revenue.
</br>
Deep discounts significantly reduce profit.
</br>
Slower shipping speeds tend to yield better profitability.
</br>
![](https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/fa9f1a6b377e3a175aaec7a01d13a3c3a05821bb/Charts/Average%20Profit%20Margin%20Category.png)
</br>
![](https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/fa9f1a6b377e3a175aaec7a01d13a3c3a05821bb/Charts/Monthy%20Profit%20Trend.png)

## 💡 Recommendations
Focus marketing on high-performing products and regions.
</br>
Reassess discount policies for low-margin items.
</br>
Optimize shipping strategies to balance cost and speed.
</br>
Develop promotional plans during high-profit months.

## 🧠 Outcome
This analysis provides data-driven insights for Superstore marketing strategy, emphasizing what are the potential areas for marketing focus to boost sales and profit.


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
└── Images |
    </br>
    └── <a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Charts/Monthy%20Profit%20Trend.png">Monthy Profit Trend.png</a>
    </br>
    └── <a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Charts/Top%205%20Products%20Profits.png">Top 5 Products Profits.png</a>
    </br>
    └── <a href="https://github.com/Omer-mohamed01/Sales-and-Profit-Analysis-Report/blob/aa0ca39b9950b287cff219cb2016daf3d6326e37/Charts/How%20Discounts%20Affect%20Profit.png">How Discounts Affect Profit.png</a>

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---
