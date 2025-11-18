# Bike Sales Data Analysis Report: Key Insights from Pivot Tables

This report summarizes the key insights derived from the bike sales data, which were generated using Pivot Tables, Pivot Charts, and various visualizations across the workbook.

## 1. Overall Performance Trend (Revenue and Profit by Year)

The annual breakdown shows a clear and consistent pattern of growth in both revenue and profit, indicating a healthy expansion of the business over the analyzed period (2017–2021).

| Year | Annual Revenue (USD) | Annual Profit (USD) |
| :---: | :---: | :---: |
| 2017 | \$10,289,670 | \$4,065,680 |
| 2018 | \$17,028,380 | \$7,747,551 |
| 2019 | \$15,705,990 | \$7,417,353 |
| **2020** | **\$22,405,052** | **\$9,909,624** |
| **2021** | **\$29,747,226** | **\$12,986,202** |
| **Grand Total** | **\$95,176,318** | **\$42,126,410** |

**Key Insight:** There was a significant acceleration in growth starting in 2020, with **2021 achieving the highest profit and revenue** of the entire period. This suggests the business is scaling successfully.

<img width="602" height="279" alt="image" src="https://github.com/user-attachments/assets/9375e97e-63a7-41f3-a74b-3ed4873e52e2" />

## 2. Revenue Breakdown by Customer Age Group

The visualization by age group highlights where the majority of the sales revenue originates, indicating the primary target demographic.

| Age Group | Total Revenue (USD) | Percentage of Total |
| :--- | :---: | :---: |
| **Adults (35-64)** | **\$47,323,876** | **49.7%** |
| Young Adults (25-34) | \$34,310,905 | 36.0% |
| Youth (<25) | \$13,201,837 | 13.9% |
| Seniors (64+) | \$339,700 | 0.4% |
| **Grand Total** | **\$95,176,318** | **100%** |

**Key Insight:** The **Adults (35-64)** segment is the largest revenue driver, accounting for nearly half of all sales. Marketing efforts should continue to be heavily focused on this group.

<img width="492" height="275" alt="image" src="https://github.com/user-attachments/assets/d420ab21-6639-4e52-83e8-fc6d367b470f" />

## 3. Revenue by Product Category and Country

The pivot table combining country and product category reveals important geographic and product-specific performance metrics.

| Country | Accessories (USD) | **Bikes (USD)** | Clothing (USD) | Grand Total (USD) |
| :--- | :---: | :---: | :---: | :---: |
| United States | \$5,819,323 | **\$21,551,497** | \$3,443,954 | \$30,814,774 |
| Australia | \$3,284,787 | **\$20,231,486** | \$1,911,313 | \$25,427,586 |
| United Kingdom | \$1,951,000 | \$8,184,668 | \$954,338 | \$11,090,006 |
| Germany | \$1,724,549 | \$7,544,500 | \$713,154 | \$9,982,203 |
| France | \$1,627,689 | \$7,378,349 | \$841,175 | \$9,847,213 |
| Canada | \$2,305,298 | \$4,317,696 | \$1,391,542 | \$8,014,536 |
| **Grand Total** | **\$16,712,646** | **\$69,208,196** | **\$9,255,476** | **\$95,176,318** |

<img width="455" height="281" alt="image" src="https://github.com/user-attachments/assets/4bf42451-3f53-4576-8fc7-f574ae14da5d" />

**Key Insights:**
* **Bikes are the core business:** Bikes generate the vast majority (over 70%) of the total revenue across all countries.
* **Top Markets:** The **United States** and **Australia** are the dominant markets, generating over 50% of the total global revenue combined.

## 4. Detailed Sales Data Attributes (Raw Data)

The raw sales data sheet provides the granular detail needed for building the pivot tables. Key attributes tracked include:
* `Date`, `Day`, `Month`, `Year` (used for time-based analysis).
* `Customer_Age`, `Age_Group`, `Customer_Gender` (used for customer segmentation).
* `Country`, `State` (used for geographic analysis).
* `Product_Category`, `Sub_Category`, `Product` (used for product mix analysis).
* `Order_Quantity`, `Unit_Cost`, `Unit_Price`, `Profit`, `Cost`, `Revenue` (the measures used in all calculations).

<img width="546" height="336" alt="image" src="https://github.com/user-attachments/assets/5ff5b56d-32a9-4253-9b77-a00b274c72e4" />

  
