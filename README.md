# Final-Project


INVENTORY MANAGEMENT ANALYSIS

Samsudeen Olawale Afolabi


PROJECT SCOPE:  The project's objective is to generate actionable insights aimed at enhancing inventory management practices, cutting costs, and elevating the overall customer experience by ensuring real-time product availability. The key focus areas include:



1) Optimizing Inventory Levels:

Provide recommendations for optimal inventory levels encompassing essential factors like reorder points and Economic Order Quantity (EOQ).
EOQ will be determined to identify the ideal order quantity, minimizing overall inventory costs and mitigating the risk of stockouts.
Inventory Management Strategy:


2) Offer strategic recommendations for process improvements within the inventory management lifecycle:

Propose enhancements in procurement and production processes to increase operational efficiency.
Develop a comprehensive inventory management strategy to align with organizational goals, streamline processes, and enhance overall effectiveness.


By addressing these aspects, the project aims to foster efficient inventory management, reduce operational expenses, and ensure a seamless customer experience through consistent real-time product availability.







PROJECT STEPS: 

1) Dataset Exploration, Description, Cleaning, Wrangling, and EDA:


Shape Description:


i)  Check the shape of data1, data2, and data3.



Column Description (for each dataframe):


i)  Describe each column in data1, data2, and data3. Understand the information each dataframe provides


 
 Assessment of Redundant Columns:


i)  Identify and assess columns in each dataframe that might not contribute significantly to sales analysis.



Dropping of Redundant Columns:


i)  Drop columns in each dataframe considered redundant for the  sales analysis.



Assessment of Variable Types (for each dataframe):


i)  Categorize variables in each dataframe into relevant types (e.g., product categories, sales figures).



Definition of Key Metrics:


i)  Identify key metrics across the three dataframes that align with sales analysis


 
 Merging Dataframes:


i)  Merge data2 and data3 using common columns (e.g., ProductId, StoreId).



Look for NaN Values (for each merged dataframe):


i) Check for missing values (NaN) in the merged dataframe. Removal of Rows with NaN Values (for each merged dataframe):
ii) Depending on the extent of missing data, remove or impute NaN values in the merged dataframe.



Homogenization of Data Types (for each merged dataframe):


i)  Ensure consistency in data types within columns for meaningful analysis in the merged dataframe. 


 
 Dispersion of Key Metrics:


i) Understand the distribution of key metrics across the merged dataframe. 
ii) Plot key variables believed to impact sales in the merged dataframe.






2) Trends and Patterns Analysis:



Monthly Sales Trends (using merged data frame):


i) Explore trends in monthly sales using the sales information in the merged data frame.



Promotion Impact Analysis 


i)  Assess the impact of promotions on sales, considering historical data from the merged data frame and product information from data1.



Customer Loyalty Programs (using merged data frame):


i)  Analyze the effectiveness of loyalty programs on repeat purchases using sales information from the merged data frame.


 
 Inventory Management (using merged data frame):


i)  Explore the relationship between inventory levels (from the merged dataframe) and sales.






3) Customer Behavior and Preferences:



Customer Purchase Patterns (using merged dataframe):



i)  Analyze customer behavior in terms of product preferences and purchasing patterns using sales information from the merged dataframe. 
 


Effect of Discounts (using merged dataframe and data1):


i)  Investigate how discounts on certain products (from data1) affect overall sales using sales information from the merged dataframe.



Flash Promotions and Fresh Products (using merged dataframe):


i)  Explore the impact of flash promotions, especially on fresh products and their expiration dates using sales information from the merged dataframe.




4)  Visualizations and Insights Presentation:



Tableau Visualization:


i)  Create Tableau visualizations to show trends, patterns, and design interactive dashboards showcasing insights from the analysis.



Insights Synthesis:


i)  Summarize key insights gained from the analysis across the three dataframes.



