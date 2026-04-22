# Supply Chain Control Tower Dashboard

### Objective
To design and develop an interactive Supply Chain Control Tower dashboard that provides end-to-end visibility into operational performance, including delivery efficiency, inventory health, and warehouse performance. The objective is to enable stakeholders to monitor KPIs, identify risks, and support data-driven decision-making in supply chain operations.

<img width="3724" height="1620" alt="image" src="https://github.com/user-attachments/assets/93ba8150-9cb9-48d4-9612-fcc785e136da" />

### Source
The dataset used in this project is a simulated multi-source supply chain dataset modeled to reflect real-world enterprise operations. It includes data across orders, shipments, inventory, products, suppliers, and warehouse performance to replicate a realistic supply chain environment.

### Tools
- SQL for data extraction and transformation logic  
- Excel for data cleaning, preprocessing, and validation  
- Tableau for dashboard development, data modeling, and visualization  

### Data Cleaning and Preparation
- Validated and standardized data across multiple tables including orders, inventory, shipments, and warehouses  
- Handled missing and inconsistent values to ensure data integrity  
- Created relationships between datasets using common keys such as SKU and Warehouse ID  
- Structured data to support multi-grain analysis at SKU level and warehouse level  
- Optimized data for visualization by aggregating key fields and ensuring correct data types  

### Exploratory Data Analysis
- Analyzed distribution of order fulfillment statuses including on-time, delayed, and backordered  
- Evaluated inventory levels and daily demand patterns across SKUs  
- Identified variability in warehouse throughput and shipment delays  
- Explored relationships between inventory levels, demand, and delivery performance  

### Data Analysis
- Developed key KPIs including On-Time Delivery percentage, Fill Rate, Backorders, Revenue, and Profit  
- Created calculated fields to measure Inventory Days of Cover, Delay percentage, and Stockout Risk classification  
- Performed multi-dimensional analysis across SKUs, warehouses, and time  
- Built geospatial visualization to analyze warehouse-level performance  
- Implemented interactive filters and dashboard actions for drill-down analysis  

### Results and Findings
- Identified SKUs with low inventory coverage and high demand, indicating potential stockout risks  
- Highlighted warehouses with higher delay rates impacting overall delivery performance  
- Observed inconsistencies between delivery performance and inventory availability across regions  
- Detected operational inefficiencies contributing to backorders and delayed shipments  

### Recommendations
- Implement proactive inventory planning for SKUs with low days of cover  
- Prioritize operational improvements in high-delay warehouses  
- Introduce automated alerts for KPI threshold breaches such as low On-Time Delivery percentage  
- Optimize demand forecasting to better align inventory with consumption patterns  
- Enhance real-time data integration for faster decision-making

### How to Use
- Open the Tableau workbook file in Tableau Desktop  
- Use KPI cards at the top to monitor overall supply chain performance  
- Interact with the warehouse map to filter and analyze specific locations  
- Use filters such as Stockout Risk and Warehouse to focus on critical areas  
- Review the inventory risk table to identify high-risk SKUs and take action  

### Use Cases and Value
- Provides centralized visibility into supply chain operations  
- Helps identify high-risk inventory and potential stockouts early  
- Supports prioritization of warehouse and SKU-level issues  
- Enables faster operational decision-making through interactive analysis  
- Improves monitoring of key performance metrics across the supply chain  

### Conclusion
This project demonstrates the development of an interactive supply chain analytics solution that consolidates operational data into a unified dashboard. By combining KPI tracking, inventory risk analysis, and geospatial insights, the dashboard enables organizations to monitor performance, identify bottlenecks, and improve overall supply chain efficiency.
