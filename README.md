# PowerBi_Projects

# Product & Tax Analysis Dashboard

## 🚀 Project Overview
A comprehensive, dual-view Power BI dashboard designed to provide a holistic analysis of business performance. This report allows stakeholders to seamlessly switch between analyzing core product metrics (Sales, Profit, Orders) and examining key tax-related figures, enabling data-driven strategic decisions.

## 📊 Key Features & Analysis
This dashboard is composed of two main interactive pages:

### 1. Product Analysis Page
* **High-Level KPIs:** Tracks essential metrics including Total Orders, Total Profit, and Total Sales, with a clear Year-over-Year (YoY) growth percentage for each.
* **Dynamic Metric Slicer ("Target"):** A key interactive feature allowing users to select a metric (Total Quantity, Total Profit, Total Orders, or Sales). This selection dynamically changes the main Donut Chart to show the quarterly breakdown of the chosen metric.
* **Time-Based Filtering:** Users can easily filter the entire report by Month, Quarter, and Year to drill down into specific periods.

### 2. Tax Analysis Page
* **Tax-Specific KPIs:** Monitors critical tax metrics such as Average Tax, Sales Including Tax, and Total Quantity, complete with YoY performance indicators.
* **Monthly Sales Trends:** A line chart visualizes sales performance on a monthly basis, making it easy to spot trends and seasonality.
* **Hierarchical Tax Breakdown:** An interactive drill-down visual that allows for a detailed analysis of total tax amounts by Year, Quarter, and Month, providing granular insights into tax liabilities over time.
* **Seamless Navigation:** Clear buttons allow for easy switching between the "Product Analysis" and "Tax Analysis" views.

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Used for data modeling, visualization, and creating an interactive user experience.
* **DAX (Data Analysis Expressions):** Implemented for advanced calculations including:
    * Time intelligence functions to calculate Year-over-Year (YoY) growth.
    * Dynamic measures using `SWITCH` and `SELECTEDVALUE` to power the "Target" slicer.
* **Power Query (M Language):** Utilized for data cleaning, transformation, and preparation.
* **Data Source:** (e.g., Financial Database, E-commerce Platform Data - replace with your actual data source).

## 📸 Dashboard Screenshots
A visual walkthrough of the dashboard's capabilities:

### Product Analysis View (showing Total Profit by Quarter)
[![Product Analysis - Profit View](screenshots/product_analysis_profit.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Detailed%20Dashboard%201.png)

### Product Analysis View (showing Total Orders by Quarter - demonstrates interactivity)
[![Product Analysis - Orders View](screenshots/product_analysis_orders.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Detailed%20Dashboard%203.png)

### Tax Analysis View
[![Tax Analysis View](screenshots/tax_analysis.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Detailed%20Dashboard%202.png)

## 💡 Learnings & Insights
* **Insight:** The dashboard effectively demonstrates the relationship between high sales periods and their corresponding tax implications, providing a more complete business picture.
* **Challenge Addressed:** The main technical challenge was creating the dynamic "Target" slicer. This was solved by writing a flexible DAX measure using the `SWITCH` function, which changes the calculation based on the user's selection, making the report highly interactive and user-friendly.






# HR Attrition Analysis Dashboard

## 🚀 Project Overview
This interactive Power BI dashboard is designed to analyze and identify the key drivers behind employee attrition within an organization. It aims to empower HR departments with actionable insights to understand patterns, mitigate risks, and improve employee retention strategies.

## 📊 Key Features & Analysis
* **Overall Attrition Performance:** Displays key metrics such as total employees, attrition rate, average monthly income of leavers, and average years since last promotion.
* **Demographic Attrition Breakdown:** Analyzes attrition based on marital status, age groups, and education fields.
* **Job Role Impact:** Identifies specific job roles and departments experiencing higher attrition rates.
* **Interactive Filters:** Allows users to dynamically slice and dice data by distance segment, experience level, gender, marital status, and income segment for deeper insights.
* **Overtime Impact:** Highlights the number of employees who work overtime among those who left.

## 🛠️ Tools & Technologies
* **Power BI Desktop:** For data modeling, report design, and visualization.
* **DAX (Data Analysis Expressions):** Utilized for complex calculations and custom measures (e.g., Attrition Rate, Monthly Income for Attrited Employees).
* **Power Query (M Language):** Employed for data extraction, transformation, and loading (ETL) processes to clean and prepare raw data.
* **Data Source:** (e.g., Employee HR Data CSV, SQL Database - replace with your actual data source).

## 📸 Dashboard Screenshots
Here's a visual overview of the dashboard pages:

### Attrition Analysis Overview
https://github.com/Adham-spec/PowerBi_Projects/blob/main/ScreensHR/HR%20Attrition%20Dashboard%20Overview.png
### Exploring Attrition Reasons by Job Role and Education
[[![HR Attrition Reasons]([Dashboard Dark 2.png](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Dasboard%20Dark%202.png))](https://github.com/Adham-spec/PowerBi_Projects/blob/main/HR%20Attrition%20Dashboard%20Overview.png)
## 💡 Learnings & Insights

* **Insight 1:** Understanding how specific job roles contribute disproportionately to overall attrition.
* **Insight 2:** Identifying correlation between factors like overtime and attrition rates.
* **Challenge Addressed:** (e.g., "Ensuring data integrity from multiple HR data extracts and transforming it into a cohesive model for analysis was a key challenge overcome using Power Query.")


# ProAnalytix: Comprehensive Business Analysis Dashboard

## 🚀 Project Overview
ProAnalytix is a holistic, multi-page Power BI dashboard designed to provide a 360-degree view of business operations. This comprehensive solution integrates analysis across four key pillars: Sales, Products, Returned Orders, and Production. The dashboard empowers decision-makers to move seamlessly from high-level sales performance to granular production-line metrics, all within a single, unified environment.

## 📊 Key Features & Analysis
The dashboard is structured into four dedicated analytical pages, accessible via an intuitive navigation pane:

### 1. Sales Analysis
* **Core KPIs:** Tracks Total Orders, Total Sales, and Total Products to provide a quick snapshot of sales activity.
* **Performance Breakdown:** Visualizes sales performance by Region, Product Category, Quarter, and Month, allowing for detailed trend analysis.

### 2. Product Analysis
* **Cost-Centric KPIs:** Focuses on key cost metrics including Average Price Per Product and Total Cost.
* **Geographical Cost Distribution:** Analyzes total cost distribution by Region and Country.
* **Temporal Cost Trends:** Provides insights into how costs fluctuate on a quarterly and monthly basis.

### 3. Returned Orders Analysis
* **Returns Monitoring:** Tracks critical return metrics such as Number of Returned Orders, Sales Value of Returns, and the overall Returns Rate.
* **Root Cause Analysis:** A key feature that breaks down returns by complaint description (e.g., "Size not correct", "Broken part"), providing actionable feedback for quality improvement.
* **Regional & Seasonal Patterns:** Identifies if certain regions or times of the year have higher return rates.

### 4. Production Analysis
* **Operational Efficiency KPIs:** Monitors production output with metrics like Total Actual Quantity, Total Hours, and Count of Downtime events.
* **Machine & Work Center Performance:** Analyzes production quantity, duration, and downtime by specific Machine Type and Work Center, helping to identify bottlenecks and areas for improvement.

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Used for end-to-end development, from data modeling and transformation to creating the final interactive visualizations.
* **DAX (Data Analysis Expressions):** Implemented for a wide range of calculations, including aggregation (Total Sales, Total Cost) and performance rates (Returns Rate).
* **Power Query (M Language):** Utilized for extensive data cleaning, shaping, and integrating data from multiple business functions (Sales, Production, etc.).
* **Data Source:** (e.g., Enterprise Resource Planning (ERP) System, multiple CSV files - replace with your actual data source).

## 📸 Dashboard Screenshots
A visual tour of the four main analysis pages:

### Sales Analysis Page
[![Sales Analysis](screenshots/sales_analysis.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Screenshot%202025-10-17%20015423.png)

### Product Analysis Page
[![Product Analysis](screenshots/product_analysis.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Screenshot%202025-10-17%20015520.png)

### Returned Orders Analysis Page
[![Returned Orders Analysis](screenshots/returned_orders_analysis.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Screenshot%202025-10-17%20015557.png)

### Production Analysis Page[
[![Production Analysis](screenshots/production_analysis.png)](https://github.com/Adham-spec/PowerBi_Projects/blob/main/Screenshot%202025-10-17%20015657.png)


## 💡 Learnings & Insights
* **Holistic Insight:** This project demonstrates the power of creating a connected data story. For example, one could potentially correlate a spike in "Downtime by Work Center" (Production page) with a subsequent increase in "Returns by Complaint Description" for "Broken part" (Returns page).
* **Challenge Addressed:** A primary challenge was developing a robust and optimized data model that could efficiently serve four distinct yet interconnected areas of analysis without sacrificing performance. This was achieved through careful schema design and relationship management in Power BI.


  
