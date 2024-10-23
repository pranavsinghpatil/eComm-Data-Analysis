
# E-commerce Power BI Dashboard 


## Project Overview

This project is an interactive Power BI dashboard developed to visualize key insights for an e-commerce platform. The dashboard offers a seamless experience with both **Dark** and **Light Mode** support and an optimized filters panel to enhance user interaction. 

It includes a **Finance Dashboard**, **Sales and Marketing Dashboards**, and a **Regional Analysis Dashboard** with crucial performance measures.

## Demo Video
*You can download or watch the demo video of the Power BI dashboard [here](./DEMO/ScreenRecording 2024-10-21 0.mp4).*

## Getting Started
### Requirements
- Power BI Desktop (version  2.137.751.0 or higher)
- E-commerce dataset (or replace with your own adjacent data)


## Usage
1. Open the project in Power BI Desktop.
2. Use the filter panel to refine the data displayed in each dashboard.
3. Toggle between dark and light modes based on your preference.
4. Explore the finance, sales, and regional analysis dashboards to gain insights


## Features

### 1. Dark and Light Mode
- **Dynamic theme switching**: The dashboard supports both dark and light themes, allowing users to toggle between modes for visual comfort.


### 2. Optimized Filters Panel
- The **filters panel** has been optimized to provide an intuitive user experience, allowing for quick data slicing across various dimensions like region, customer segments, and time periods.
- ![Project Screenshot](screenshots/FiltersPanel(lightMode).png)

### 3. Finance Dashboard
- This dashboard includes critical financial measures such as profit margins, gross profit, operating expenses, and return on equity to track the overall financial health of the e-commerce business.
- ![Project Screenshot](screenshots/Finance_dashboard.png)

### 4. Sales and Marketing Dashboards
- Two dashboards focus on **Sales Performance** and **Marketing Effectiveness**:
  - Track key metrics like sales growth rate, total sales, and average order value.
  - Marketing measures such as leads, conversion rates, and opportunities help analyze marketing ROI.
- ![Project Screenshot_1](screenshots/Sales&Marketing_1.png)
- ![Project Screenshot_2](screenshots/Sales&Marketing_2.png)


### 5. Regional Analysis Dashboard
- Visualize sales and performance data segmented by **regions** with the ability to toggle between **Dark** and **Light Mode**. The dashboard shows insights like average order value by region and top-performing regions in sales.
- ![Project Screenshot](screenshots/Screenshot 2023-05-29 002515.jpg)

### 1. Data Model View
- The data model provides a high-level overview of the relationships between various tables such as `Orders`, `Returns`, `Location`, and `People`. It shows how the data is structured and connected, ensuring efficient filtering and reporting across different dashboards.
- ![Data Model View](screenshots/Model_View.png)


## Data Sources
The project is designed to work with e-commerce data. The data includes:
- **Sales Data**: Order details, revenue, and profit.
- **Marketing Data**: Campaign performance, customer engagement, and conversion rates.
- **Regional Data**: Sales and performance breakdown by region.



## Key Measures

The project includes a variety of **DAX measures** to analyze different aspects of business performance:

### 1. Channel Measures
- **LargestChannel**: Identifies the channel with the most orders.

- **MaxOrderChannel**: Measures the maximum orders placed through any channel.

 
### 2. Customer Measures
- **Average Time to Conversion (in Days)**: Calculates the average time taken for customers to convert.

- **C_Total Customers**: The total number of customers.

- **New Customers**: The count of new customers acquired.


### 3. Delivery Measures
- **Delivery Percentage**: Tracks the percentage of deliveries completed on time.
 
- **Largest Delivery Agency**: Identifies the delivery agency handling the largest volume of orders.


### 4. Finance Measures
- **F_Debt-to-Equity Ratio**: A financial leverage ratio showing the proportion of debt to equity.

- **F_Gross Margin**: Gross profit as a percentage of sales.
 
- **F_Operating Expenses**: Total operating expenses incurred by the company.
 
- **F_Net Profit**: The company’s net profit after all expenses.
 
- **F_Return on Equity (ROE)**: Measures the profitability relative to shareholders' equity.

- **Gross Profit_SPLY**: Gross profit compared to the same period last year.
 
- **Sales_SPLY**: Sales compared to the same period last year.


### 5. Marketing/Regional Measures
- **M_Average Order Value (AOV)**: The average value of each order.

- **M_No of Leads**: Total number of marketing leads generated.
 
- **M_Opportunities Conversion Rate**: The conversion rate of leads to opportunities.
 
- **MaxAvgOrderWeekday**: The day of the week with the highest average orders.

 

### 6. Sales Measures
- **S_Avg Sales**: The average sales value.

- **S_SalesGrowthRate**: Growth rate of sales over a period.
 
- **S_Total Sales**: The total sales value for the selected time period.
 
- **S_TotalUnitsSold**: The total number of units sold.
 

### 7. Profits Measures
- **P_Avg Profit**: The average profit per transaction.
 
- **P_Net Profit**: The overall net profit.

- **P_Profit Margin**: Profit margin percentage.



---

## Installation

1. Download or clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Customize data sources as per your requirement.
4. View and interact with the dashboards in Power BI Desktop.


---

## Future Improvements

- **Automation**: Add automation to update data sources in real-time.
- **Enhance Filters**: Introduce additional filter options for advanced segmentation.
- **Interactive Insights**: Add more interactive elements to enhance user experience.
- **Predictive Analytics**: Add forecasting capabilities for future sales and financial performance.
- **Live Data Integration**: Connect real-time data sources to keep the dashboard updated automatically.
- **Customization Options**: Allow users to add custom metrics or KPIs.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

