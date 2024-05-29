# E-commerce-Sales

Project Overview
The project involves converting an Excel file into a CSV file, transforming the data, and creating a comprehensive dashboard using Power BI. The dashboard includes key performance indicators (KPIs) and various visualizations to facilitate data-driven decision-making.

Data Transformation
Conversion: Converted the provided Excel file into a CSV format.
Data Enrichment: Added columns from the Item Master file, including Sub-category, Phase, Color, Variants, Size, and Configuration Number.
Dashboard Creation
The CSV file was loaded into Power BI, where the following KPIs and metrics were analyzed:

Total Sales: Total sales for the entire month.
Total Discount Sales: Sales from discounted articles.
Total Orders: Number of orders placed in the month.
Delivered Orders: Number of orders delivered.
Cancelled Orders: Number of orders canceled.
Returned Orders: Number of orders returned.
Delivery TOT (Turnaround Time): Created using a DAX query with the DATEDIFF function to calculate the delivery time from order placement to delivery.
Min Delivery TOT: Minimum delivery time.
Max Delivery TOT: Maximum delivery time.
Filters Used
Order Date: To display the number of orders on specific days.
Fulfillment Status: To show delivered and in-process orders.
Order Status: To show the status of orders including Approved, Awaiting Assigning, Cancelled, City Issue, Dead, Delivered, Dispatch Issue, Dispatched, Pending CC, Pending COD, and Returned.
Visualizations
Stacked Bar Chart:
Products: Most sold products.
Variants: Color, size, style ID, and configuration.
Phase: Phase with the most sales.
Sub-category: Category with the most sales.
Area Chart:
Shipping Location: City with the most sales.
Donut Chart:
Shipping Method: Courier service delivering the most orders.
Stacked Column Chart:
Discount per Day: Sales based on discounts.
Analysis and Insights
Delivery Turnaround Time (TAT): The average TAT was above the acceptable threshold. It should ideally be around 3 days, with a maximum acceptable TAT of 7 days. However, the maximum observed was 15 days, influenced by the Eid holiday backlog.
Coupon Discounts: The highest usage of discount coupons was on July 18th.
Sales Peak: The highest sales were on July 11th.
Top Sales Locations: Karachi had the most sales, indicating a need to target rural areas more effectively.
Popular Phases: The Summer 2023 Regular phase saw the most sales due to discounts, especially in the AK Fashion Pret Eastern sub-category.
Popular Products: Unstitched two-piece and one-piece articles were the most ordered, particularly black color variants in Cambric and Lawn configurations.
Order Issues: Returned and canceled orders accounted for around 7% of total orders, likely due to delivery delays or incorrect sizes/articles delivered.
