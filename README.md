# E-Commerce sales Analysis using Power BI

<img width="629" height="280" alt="image" src="https://github.com/user-attachments/assets/4d01a847-f901-4e1e-b8f4-6c1685b8c4e7" />


## 📑 Table of Contents
* [Project Overview](#-project-overview)
* [Data Sources & Architecture](#-data-sources—architecture)
* [Calculation](#-Calculation)
* [Data Visualization](#-Dat-Visualization)
* [Key Insights](#-key-insights)
* [How To Use](#-how-to-use)

## 🎯 Project Overview

* **Business Problem:** Analyze product order distributions, category profit margins, and sub-category sales performance to identify key growth drivers and optimize the store's product portfolio.
  
* **Objective:** This project focuses on organizing, analyzing, from a different type of datasets. The data sets are Sales Target, List of Order, Order Details. Using Power BI tool, the workflow transforms raw datasets into a structured summary.
  
* **Target Audience:** To increase the sales perfomance and the primary user as customer.

## 🗃️ Data Sources & Architecture

* **Source Systems:** Local CSV files.
  
* **Storage Mode:** Specify if using Import, Direct Query, or Composite mode.

## ⚙️ Calculation
* Calculation done as per the business requirement. one of the example calculation shown below,
```dax
YTD Sales = TOTALYTD(SUM('Order Details'[Amount]),'Order Details'[Order Date],'Order Details'[Order Date])
```
## ⚙️ Data Visualization
* Visualization done as per the business requirement. sample visualization shown below,
  
  <img width="741" height="472" alt="Max Profit Margin " src="https://github.com/user-attachments/assets/74a3ad56-fb80-4bfd-8488-85939b0b1d93" />

  ## 💡 Key Insights
  
* **Trend A:** First major business finding or behavior pattern identified.
* **Trend B:** Actionable performance anomaly noted in the data.
* **Recommendation:** Direct business action suggested based on the metrics.

  ## 🚀 How To Use
1. **Prerequisites:** Ensure you have the latest Power BI Desktop installed.
2. **File Formats:** Clone the repository to access the `.pbix` or `.pbit` file.
3. **Data Refresh:** Change the source path under **Data Source Settings** to point to your data files.

## Author

**Abirami Ganesan**



