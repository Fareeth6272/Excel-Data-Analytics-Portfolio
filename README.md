# Speed Bikes Store: Customer & Sales Performance Analysis (Excel Dashboard)



## Project Overview

This project focuses on analyzing sales data from "Speed Bikes Store" to provide actionable insights into customer purchasing behavior. The primary objective is to empower the store owner with data-driven understanding of their customer base, enabling them to optimize marketing, sales strategies, and ultimately drive future growth.

## Business Problem

Speed Bikes Store, like many growing retailers, currently relies on general assumptions for sales and marketing strategies. This lack of granular, data-driven insight into customer demographics, preferences, and purchasing patterns means they're likely missing significant opportunities to optimize marketing spend, refine inventory decisions, and unlock untapped sales potential. This project directly addresses this gap by providing actionable intelligence on their most valuable customer segments, enabling the store to move beyond guesswork to truly data-informed strategies for sustainable growth.

## Technical Skills Demonstrated

* **Data Cleaning & Preprocessing:** Handling missing values, standardizing data types and formats.
* **Excel Formulas:** Use of aggregate functions (e.g., SUMIFS, COUNTIFS, AVERAGEIFS), logical functions (e.g., IF) for data manipulation and calculation.
* **Pivot Tables & Pivot Charts:** Advanced data summarization and visualization from various perspectives.
* **Interactive Dashboard Design:** Integrating multiple charts and tables for a cohesive and dynamic user experience.
* **Slicers & Timelines:** Enabling interactive filtering and drill-down capabilities within the dashboard.
* **Data Visualization:** Creating clear, effective, and aesthetically pleasing charts.

## Dataset Used

The analysis uses a synthetic sales dataset, available here:
[Excel Project Dataset.xlsx](https://github.com/Fareeth6272/Data-Analytics-Portfolio/blob/main/Excel%20Project%20Dataset.xlsx)

## Key Questions (KPIs) Addressed

1.  **Gender Distribution of Purchases:** Who purchased more bikes - Men or Women?
2.  **Age Category Performance:** Which age category of customers purchased the most bikes?
3.  **Commute Distance Impact:** What is the typical commute distance of the customers who purchased bikes?
4.  **Regional Sales Performance:** Which geographic region generated the most sales?
5.  **Education Level & Purchases:** What type of educated people purchased the most bikes?

## Process

1.  **Data Acquisition & Initial Review:** Loaded the raw sales data into Excel and performed an initial check for structure and content.
2.  **Data Cleaning & Consistency:**
    * Identified and addressed minor inconsistencies in text entries (e.g., ensuring consistent capitalization).
    * Verified and corrected data types for all columns (e.g., ensuring 'Sales' and 'Customer ID' were numerical, 'Date' was in date format).
    * Checked for any blank or missing values across critical columns and confirmed their impact was negligible or handled appropriately.
3.  **Data Transformation & Analysis:**
    * Created `Age Category` groups based on customer age for easier analysis.
    * Utilized **Pivot Tables** to aggregate sales data by each KPI (Gender, Age Category, Commute Distance, Region, Education).
    * Generated **Pivot Charts** from these tables to visually represent the findings.
4.  **Interactive Dashboard Creation:**
    * Consolidated all relevant pivot charts and key insights onto a single, organized dashboard sheet.
    * Implemented **Slicers** for `Gender`, `Age Category`, and `Region` to provide dynamic filtering, allowing the store owner to explore specific segments interactively.

## Dashboard Snapshot

file:///C:/Users/Abdul/Pictures/Screenshots/Screenshot%202025-02-23%20200339.png

*(For full interactivity, please download the `Bike_Sales_Dashboard.xlsx` file and open in Microsoft Excel.)*

## Key Project Insights

* **Gender:** Male customers are the primary purchasers, accounting for approximately **60%** of all bike sales, significantly more than female customers.
* **Age Category:** The **35-44** and **45-54** age categories represent the largest buying segments, indicating a strong market among middle-aged individuals.
* **Commute Distance:** Customers with a commute distance of **0-1 miles** show the highest purchasing frequency, suggesting a demand for bikes for local errands or short recreational rides.
* **Region:** The **Europe** region leads in sales volume, followed by North America, highlighting key geographic markets.
* **Education:** Individuals with a **Graduate Degree** are the most frequent bike buyers, suggesting a correlation between higher education levels and bike ownership in this dataset.

## Final Conclusion & Business Recommendations

Based on this analysis, the Speed Bikes Store should:

1.  **Target Middle-Aged Males:** Focus marketing and sales efforts primarily on male customers aged 35-54, as this segment demonstrates the highest propensity to purchase bikes.
2.  **Emphasize Local Commuting & Lifestyle:** Tailor marketing content to highlight the convenience, health benefits, and lifestyle aspects of owning a bike for short commutes (0-1 miles) or recreational purposes within the local vicinity.
3.  **Prioritize European Market:** Allocate more resources to marketing and sales initiatives within the European region, given its current leading sales performance. Consider region-specific promotions.
4.  **Educational Alignment:** Explore partnerships or tailored promotions targeting universities or professional organizations, as graduate-degree holders represent a significant customer base.

By implementing these data-driven strategies, Speed Bikes Store can more effectively engage their core customer base, optimize inventory, and ultimately drive higher sales and sustainable growth.

## Future Work

* Conduct a deeper analysis into product-specific sales trends within each customer segment.
* Explore seasonality of sales to optimize inventory and marketing campaigns throughout the year.
* Integrate customer feedback surveys to understand purchase motivations beyond demographic data.
* Analyze the impact of marketing channels on sales for different customer segments.
