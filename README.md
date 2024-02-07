# AdventureWorks (Overview-Operational Report-Inventory Report)

Welcome to the AdventureWorks Power BI project documentation. This report provides a comprehensive analysis of the AdventureWorks sample database, offering insights into overall company performance, operational efficiency, and product inventory. The project is organized into three main pages: Overview, Operational Report, and Inventory Report.</br>

## Project Overview:</br>
Conductivity Mode: Direct Query (Switched to Import Mode)</br>
Data Source: AdventureWorks Sample Database</br>
## Report Pages:
### Overview:
General View: Provides an overall snapshot of key areas, salespersons, order frequency, and top products.</br>
Interactive Visuals: Users can explore and interact with different aspects of the company's performance.</br>

![overview](https://github.com/NouraAlgohary/AdventureWorks-Overview-OperationalReport-InventoryReport-/assets/103903785/d904c477-3993-46af-9a9d-5d658485de12)

### Operational Report:

Sales Team Performance: Evaluate the performance of sales teams for recognition and comparison.</br>
Comparison Features: Allows users to compare current performance with others and analyze month and quarter-over-quarter trends.

![operational_report](https://github.com/NouraAlgohary/AdventureWorks-Overview-OperationalReport-InventoryReport-/assets/103903785/5a2f29d4-2928-4a19-a3a5-62276c4caf3c)

### Inventory Report:

Product Inventory Insights: Offers detailed insights into product inventory and related metrics.

![inventory_report](https://github.com/NouraAlgohary/AdventureWorks-Overview-OperationalReport-InventoryReport-/assets/103903785/df6014cc-92bd-49d8-ba15-37e02176ce75)


## Implementation Steps:
### Data Extraction:
Utilized Direct Query initially to connect to the AdventureWorks sample database. This mode allows for a live connection, ensuring real-time data updates and analysis.</br>

### Switch to Import Mode for Modeling:
After the initial exploration and data extraction, switched to Import Mode for data modeling. Import Mode offers enhanced performance and responsiveness during the modeling process.</br>

### Data Modeling:
Model data into a Star Schema, establishing relationships among tables. The Star Schema provides a structured and efficient way to organize data for improved query performance.</br>

![image](https://github.com/NouraAlgohary/AdventureWorks-Overview-OperationalReport-InventoryReport-/assets/103903785/cc4d0320-51c7-4220-8238-0b02bde88061)


### Create Measures:
Developed DAX measures for key performance indicators, including metrics such as the number of orders, total subtotal, total tax, total freight, and total due. These measures serve as essential data points for analysis and decision-making.</br>

### Data Visualization:
Designed visually appealing and informative charts and graphs for each report page. The visualizations provide a clear representation of the data, facilitating easy understanding and interpretation.

### Advanced Visualization Techniques:
Implemented interactive features such as tooltips, drilldown, and drillthrough for a richer user experience. Tooltips offer additional context and details on data points, while drilldown and drillthrough functionalities allow users to explore specific aspects of the data in more detail.
