# Global SuperStore Analysis

### Dashboard Link : https://github.com/emadfayed011190/Global-SuperStore-Analysis/blob/main/Global%20SuperStore1.pbix
### snaps link : https://github.com/emadfayed011190/Global-SuperStore-Analysis/commit/6a93bb7790ee50d83691514fccc53555a8367966

## 1. Introduction

This document outlines the business requirements for creating a series of dashboards focused on product and sales analysis for the Global SuperStore. The goal is to provide actionable insights into sales performance, cost management, and profit generation across different dimensions.

## 2. Objectives

- To analyze sales, costs, and profits by product categories, years, and geographical locations.
- To visualize trends over time to support strategic decision-making.
- To identify high-performing and underperforming segments that require attention.

## 3. Scope

The dashboards will cover the following areas:

1. **Product Analysis**
   - Total sales, cost, and profit figures.
   - Breakdown of cost and profit by product category.
   - Year-over-year analysis of cost and profit.

2. **Geographical Analysis**
   - Sales and profit visualization by state and country.
   - Mapping of sales performance across different regions.

3. **Customer Segmentation**
   - Analysis of sales and profit by customer segment.
   - Average shipping costs by sub-category and shipping mode.

## 4. Business Requirements

### 4.1 Data Requirements

- **Data Sources**: 
  - Sales data from orders.
  - Customer data including demographics and segmentation.
  - Product data including categories and sub-categories.
  - Geographic data for mapping purposes.

- **Data Attributes**:
  - Sales Amount.
  - Cost Amount.
  - Profit Amount.
  - Product Category.
  - Customer Segment.
  - Geographic Location (State, Country).

### 4.2 Functional Requirements

- **Dashboard Features**:
  - Interactive visualizations (bar charts, line graphs, maps).
  - Filters to allow users to customize views by year, category, and region.
  - Export functionality for reports (PDF, Excel).

- **User Interface**:
  - Clear and intuitive layout for easy navigation.
  - Consistent color scheme and branding aligned with Global SuperStore.

### 4.3 Reporting Requirements

- **Performance Metrics**:
  - Total Sales, Cost, and Profit figures.
  - Year-over-year growth in sales and profit.
  - Comparison of performance across product categories and regions.

- **Alerts and Notifications**:
  - Highlight significant changes in sales or profit trends.
  - Identify areas that fall below expected performance thresholds.

## 5. Non-Functional Requirements

- **Usability**: Dashboards should be user-friendly and accessible to users with varying levels of technical expertise.
- **Performance**: Dashboards must load data and visualizations quickly to enhance user experience.
- **Security**: Ensure that sensitive data is protected and access is controlled based on user roles.

## 6. Success Criteria

- Dashboards are deployed successfully and meet the outlined functional and non-functional requirements.
- Users report improved insights and decision-making capabilities.
- Increased engagement with the dashboards, measured by usage metrics.

## 7. Conclusion

This document serves as a foundation for developing dashboards that will provide valuable insights into the sales and product performance of the Global SuperStore. By adhering to these business requirements, the project aims to enhance data-driven decision-making across the organization.

## PROBLEM STATEMENT  
### KPI’s (Key Point Indicators)  

# Key Performance Indicators (KPIs) for Product and Sales Analysis Dashboards

## 1. Overview

The following KPIs will help measure the performance of the Product and Sales Analysis Dashboards for the Global SuperStore, focusing on sales, costs, profits, and operational efficiency across various dimensions.

## 2. Key Performance Indicators

### 2.1 Sales KPIs

1. **Total Sales Revenue**
   - **Definition**: The total sales generated over a specific period.
   - **Current Value**: $619,296.10

2. **Sales Growth Rate**
   - **Definition**: The percentage increase in sales compared to the previous year.
   - **Formula**: \((\text{Current Year Sales} - \text{Previous Year Sales}) / \text{Previous Year Sales} \times 100\)

3. **Sales by Category**
   - **Definition**: Total sales segmented by product categories (e.g., Furniture, Office Supplies, Technology).
   - **Current Example**: 
     - Furniture: $177.55K
     - Office Supplies: $166.80K
     - Technology: $204.31K

### 2.2 Cost and Profit KPIs

4. **Total Cost**
   - **Definition**: The total costs incurred in generating sales.
   - **Current Value**: $548,661.17

5. **Total Profit**
   - **Definition**: Total profit calculated after deducting costs from sales.
   - **Current Value**: $70,634.93

6. **Profit Margin**
   - **Definition**: The percentage of profit relative to total sales.
   - **Formula**: \((\text{Total Profit} / \text{Total Sales Revenue}) \times 100\)

### 2.3 Yearly Performance KPIs

7. **Cost and Profit by Year**
   - **Definition**: Year-over-year analysis of costs and profits.
   - **Example Values**: 
     - 2011: Cost: $102.60K, Profit: $11.78K
     - 2014: Cost: $164.59K, Profit: $23.80K

### 2.4 Geographic Performance KPIs

8. **Sales by Country/State**
   - **Definition**: Total sales revenue segmented by geographical locations.
   - **Example**: Afghanistan's total sales: $619,296.10

9. **Top Performing Regions**
   - **Definition**: Identification of regions with the highest sales and profits.
   - **Example**: State with highest sales and profit highlighted in the dashboard.

### 2.5 Customer Segmentation KPIs

10. **Sales by Customer Segment**
    - **Definition**: Total sales revenue segmented by customer types (e.g., Consumer, Corporate).
    - **Example Values**: Consumer, Corporate, Home Office.

11. **Average Shipping Cost by Segment**
    - **Definition**: Average shipping cost segmented by product sub-categories and shipping modes.
    - **Example**: Average shipping costs for tables, copiers, etc.

### 2.6 Efficiency and Operational KPIs

12. **Average Order Value (AOV)**
    - **Definition**: The average amount spent per order.
    - **Formula**: Total Sales Revenue / Total Number of Orders

13. **Shipping Cost as a Percentage of Sales**
    - **Definition**: Ratio of shipping costs to total sales.
    - **Formula**: \((\text{Total Shipping Costs} / \text{Total Sales Revenue}) \times 100\)

### 2.7 User Engagement KPIs

14. **Dashboard Usage Rate**
    - **Definition**: Frequency of dashboard access by users.
    - **Formula**: Total Number of Dashboard Views / Total Active Users

15. **User Satisfaction Score**
    - **Definition**: Average rating from user feedback regarding dashboard usability and insights.
    - **Collection Method**: User surveys post-dashboard use.

## 3. Conclusion

These KPIs will provide a robust framework for evaluating the effectiveness of the Product and Sales Analysis Dashboards, enabling data-driven decisions and strategic planning for the Global SuperStore. Regular monitoring of these indicators will facilitate insights into performance trends and operational efficiencies.


## PROBLEM STATEMENT
### Charts Requirements

# Chart Requirements for Product and Sales Analysis Dashboards

To effectively visualize the data in the Product and Sales Analysis Dashboards for Global SuperStore, the following chart requirements should be considered:

## 1. Sales and Profit Visualization

### 1.1 Bar Chart: Cost and Profit by Category
- **Purpose**: To compare total costs and profits across different product categories.
- **Data Required**: Sales, costs, and profits segmented by category (e.g., Furniture, Office Supplies, Technology).
- **Design Elements**:
  - Dual bars for each category to represent cost and profit.
  - Clear labeling of axes and categories.

### 1.2 Line Chart: Cost and Profit by Year
- **Purpose**: To visualize trends in costs and profits over multiple years.
- **Data Required**: Yearly sales, costs, and profits.
- **Design Elements**:
  - Lines for cost and profit, with markers for each year.
  - X-axis for years and Y-axis for monetary values.

## 2. Geographic Visualization

### 2.3 Map: Sales and Profit by State/Country
- **Purpose**: To display sales and profit distribution geographically.
- **Data Required**: Sales and profit data segmented by state or country.
- **Design Elements**:
  - Color-coded markers to indicate sales and profit levels.
  - Tooltips showing detailed data on hover.

## 3. Customer Segmentation Visualization

### 3.1 Stacked Bar Chart: Sales and Profit by Customer Segment
- **Purpose**: To analyze sales and profits across different customer segments.
- **Data Required**: Sales and profits segmented by customer type (e.g., Consumer, Corporate).
- **Design Elements**:
  - Stacked bars to show total sales with segments differentiated by color.
  - Clear legends to identify segments.

### 3.2 Pie Chart: Average Shipping Cost by Ship Mode
- **Purpose**: To understand the distribution of shipping costs across different shipping methods.
- **Data Required**: Average shipping costs for each shipping mode (e.g., First Class, Same Day).
- **Design Elements**:
  - Segments representing each shipping mode.
  - Percentage labels for clarity.

## 4. Performance Metrics Visualization

### 4.1 KPI Cards
- **Purpose**: To display key performance indicators such as total sales, total cost, and total profit.
- **Data Required**: Total sales, total costs, total profits.
- **Design Elements**:
  - Large, bold numbers for impact.
  - Use of icons to visually represent each KPI.

## 5. Summary and Drill-Down Options

### 5.1 Interactive Filters
- **Purpose**: To allow users to filter data based on year, region, or customer segment.
- **Design Elements**:
  - Dropdown menus or sliders for dynamic data updates.
  - Clear instructions on how to use filters.


## Steps Followed in Developing the Glpbal SuperStore Analysis Dashboards

# Steps Followed in Developing the Product and Sales Analysis Dashboards

Creating the Product and Sales Analysis Dashboards for the Global SuperStore involved a structured approach to ensure comprehensive data representation and usability. Here are the key steps followed in the development process:

## 1. Define Objectives

- **Identify Goals**: Determine the primary objectives of the dashboard, such as tracking sales performance, understanding cost dynamics, and analyzing customer segments.
- **Target Audience**: Define who will use the dashboard (e.g., sales managers, executives) and their specific needs.

## 2. Data Collection

- **Source Identification**: Identify relevant data sources, including sales transactions, customer information, and product details.
- **Data Extraction**: Gather data from various databases or spreadsheets, ensuring it is up-to-date and accurate.

## 3. Data Preparation

- **Data Cleaning**: Remove duplicates, correct errors, and handle missing values to ensure data integrity.
- **Data Transformation**: Structure the data for analysis, including aggregating sales by categories, years, and geographical locations.

## 4. KPI Selection

- **Identify Key Metrics**: Determine the key performance indicators (KPIs) essential for tracking sales and profitability, such as total sales, profit margins, and shipping costs.
- **Set Benchmarks**: Establish benchmarks for performance comparison, e.g., last year’s sales figures.

## 5. Design the Dashboard Layout

- **Wireframing**: Create a basic layout of the dashboard, deciding on the placement of charts and visual elements.
- **User Experience Design**: Focus on usability, ensuring the dashboard is intuitive and easy to navigate.

## 6. Chart Development

- **Choose Visualization Types**: Select appropriate chart types (e.g., bar charts, line charts, maps) based on the data being represented.
- **Data Integration**: Connect the visualizations to the prepared data sources, ensuring they update dynamically.

## 7. Interactivity Features

- **Incorporate Filters**: Add interactive filters to allow users to segment data by year, customer type, or geographic location.
- **Tooltips and Drill-Downs**: Enable tooltips for additional data insights and drill-down capabilities for detailed analysis.

## 8. Testing and Validation

- **Review Functionality**: Test the dashboard for functionality, ensuring all links and interactive elements work correctly.
- **Validate Data Accuracy**: Cross-check visualized data against original datasets for accuracy.
.

## Conclusion

These steps collectively contribute to the successful development of the Product and Sales Analysis Dashboards, ensuring they meet the analytical needs of the Global SuperStore while providing valuable insights for strategic decision-making.



