# Indicating-Business-Performance

# Objectives : 

Your task in this exercise was to create a report showing KPIs that provided the sales team with insights into their performance in the last three months. In particular, your task was to create a report that answered various KPI-related questions:

• What are the total sales and average sales?

• What are the total sales across all regions?

• What is the total number of orders placed during this time period?

• What is the total marketing expenditure, and what is the monthly marketing expenditure?

• What is the change in sales over time for the sales teams, and how does this correlate with marketing spending?

• What sales region had the highest sales during this time period, and how did their ranking change over time?

• What is the performance of different sales regions with their advertising campaigns?

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Step 1 : Download the provided dataset to your computer.

• Create a new Power BI project.

• Import the dataset (Excel file) into your Power BI project.

• In the preview window, verify that the data appears correct.

• Select Load to import the data .

• Ensure the data types for your columns in Power Query Editor are:

         • SalesID: Whole Number

         • SalesOrderNumber: Text

         • OrderDate: Date

         • DueDate: Date

         • SalesAmount: Decimal Number

         • Region: Text

         • MarketingSpend: Decimal Number

         • SalesTeam: Text

• Close and Apply any transformations in Power Query Editor to save the changes to your dataset.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Step 2: Compute the KPI Metrics and Create Visualizations

# 1. Total Sales and Average Sales

# Total Sales:

• Select Card visualization from the Visualizations pane.

• Drag and drop Sales Amount into the Values field.

• Power BI will automatically calculate Total Sales (Sum of Sales Amount).

# Average Sales:

• Create another Card visualization.

• Drag and drop Sales Amount into the Values field.

• Change the aggregation from Sum to Average to calculate Average Sales.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/c78afbcb56f978c1933757e0e12e92edf31ee5d8/Screenshot%202.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 2. Total Sales Per Month

• Select the Multi-row Card visualization from the Visualizations pane.

• Drag and drop the Sales Amount field into the Fields well.

• Expand the Order Date field and drag and drop the Month field into the Fields well.

• This will display Total Sales per Month.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/e6bdaa3719c7cc4a2afa91a131e22547eee87842/Screenshot%203.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 3. Total Orders

• Select the Card visualization from the Visualizations pane.

• Drag and drop the Sales ID field into the Fields well.

• This will display the Total Orders (count of Sales IDs).

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/bed1f9d91b8c7b2541b827dfc731da31e908b824/Screenshot%204.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 4. Total Marketing Spend and Monthly Marketing Spend

# Total Marketing Spend

• Select the Card visualization from the Visualizations pane.

• Drag and drop the Marketing Spend field into the Fields well.

• This will show the Total Marketing Spend (sum of Marketing Spend during this time).

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/e1b58e5c0b642f3c761c9e228d6cddd1bcf14936/Screenshot%205.png)


# Monthly Marketing Spend

• Select the Multi-row Card visualization from the Visualizations pane.

• Drag and drop the Marketing Spend field into the Fields well.

• Expand the Order Date field and drag and drop the Month field into the Fields well.

• This will display Monthly Marketing Spend.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/4c9cb79e1e869fb0f84432581a25ebd27070c333/Screenshot%208.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 5. The change in sales over time for the sales teams, and how does this correlate with marketing spending

• Select the Waterfall chart from the Visualizations pane.

• Drag and drop the Sales Amount into the Y-axis field.

• Drag and drop the Month field from Order Date into the Category field. This will display sales changes over the months.

• Drag and drop the Sales Team field into the Breakdown field.

• Drag and drop the Marketing Spend into the Tooltips field to see its correlation with sales changes.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/90d3cdc11479540b53f20043db54b8e35a5806ac/Screenshot%206.png)

• Hover over each item to examine how the team performed with their advertising budget compared to the previous month.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/712f2d2b6f534221b59b4c01beee85f7c70c3c82/Screenshot%209.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 6. Region Performance and Ranking

• Select the Ribbon chart from the Visualizations pane.

• Drag and drop the Sales Amount field into the Y-axis well.

• Drag and drop the Month field from Order Date into the X-axis well to display sales changes over the months.

• Drag and drop the Region field into the Legend well.

• Drag and drop the Marketing Spend into the Tooltips field to show its value with sales changes.

• Hover over the region with the highest sales to view the tooltip. For example, hovering over the East region for July will show the sales values and marketing spend.

![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/92f2e0bc7e219e6f55690bbf2d9d05211715158e/Screenshot%207.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Step 3: Communicate Results

# Total and Average Sales: 

              Total sales from January to March: $1.04 million.
              
              Average monthly sales per order: $64.75K.

# Sales Across Regions:

              East and South regions (Team B) outperform the North and West regions (Team A), indicating better sales performance.
              
# Number of Orders:

              A total of 16 distinct orders were placed, providing insight into transaction volume.

# Marketing Expenditure:

             Total marketing spend: $126K.
              
             Marketing expenditure increased each month, aligning with the goal of boosting sales.

# Sales and Marketing Expenditure Relationship:

             Waterfall chart shows a positive correlation between sales and marketing spend.

             Team B saw a higher return on marketing spend. An additional $17K in marketing led to $223K in sales for July.

             Team A saw a lower return: An additional $20K in marketing brought $65K in sales for July.

# Region Performance and Ranking:

             East region performed best in sales.
            
             Despite significant marketing expenditure, the West region underperformed, suggesting potential issues with the advertising campaigns.
             
![image_alt](https://github.com/DSgenes/Indicating-Business-Performance/blob/763ce71c97be0f182d85a0f1395eb16818fb3973/Screenshot%201.png)
