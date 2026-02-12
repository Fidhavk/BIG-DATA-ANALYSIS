# Online Retail Sales Analysis using PySpark

*Company* : CODTECH IT SOLUTIONS

*Name* : Fathima Fidha V

*INTERN ID* : CTIS5436

*Domain* : Data Analytics

*Duration* : 4 Weeks

*Mentor* : Neela Santhosh


## Project Overview
This project analyzes the Online Retail Dataset using PySpark to discover meaningful sales insights.  
The analysis includes data cleaning, feature engineering, aggregation, and visualization of sales trends over time.

## Dataset
The dataset used in this project is the Online Retail Dataset from Kaggle.  
columns of dataset:
- InvoiceNo  
- StockCode  
- Description  
- Quantity  
- InvoiceDate  
- UnitPrice  
- CustomerID  
- Country  

##  Tools & Technologies
- Python  
- PySpark  
- Google Colab  
- Pandas  
- Matplotlib  

##  Steps Performed
1. Loaded the dataset using PySpark.  
2. Performed data cleaning (removed null values and invalid quantities).  
3. Created a new column `TotalPrice = Quantity * UnitPrice`.  
4. Extracted month from `InvoiceDate`.  
5. Aggregated monthly total sales using `groupBy`.  
6. Converted Spark DataFrame to Pandas for visualization.  
7. Plotted monthly sales trend graph.  
8. Calculated moving average and visualized sales trend with moving average.

## Visualizations
- The monthly sales trend shows variation across different months.  
- Moving average helps to smooth the trend and understand overall sales behavior.  
- This analysis can help businesses understand sales patterns and plan inventory accordingly.

## Conclusion
- Monthly sales variations reveal seasonal trends.  
- Certain months show higher sales spikes — useful for business forecasting.  
- Moving average provides a smoothed trend line to visualize overall performance.  
- Top products and top country sales help identify key revenue drivers.

This analysis can assist in inventory planning, marketing decisions, and revenue projections.



