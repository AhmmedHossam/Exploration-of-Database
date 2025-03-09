# Exploration-of-Database
SQL Exploratory Data Analysis (EDA) Project:

1-Database exploration (OBJECTS OF DATABASE):
-explore tables, columns metadata USING [select * from information_schema.REQ-OBJECT]]

2-Dimension exploration (DESCRIBTIVE DATA)
-explore the unique valuess ( categories ) for each dim USING [distinct]
to recoginze how data can be grouped 

3-Date exploration
-identify the earlist and latest datres(boundries) USING [ min/max (date dim) ] 
understand scopr of data and timespan
select min(order_date) as first_order ,  max(order_date) as last_order , datediff(year ,min(order_date),max(order_date)) as boundries_per_year
select min(order_date) as first_order ,  max(order_date) as last_order , datediff(month ,min(order_date),max(order_date)) as boundries_per_month

4-Measurments exploration ( NUMERIC DATA THAT CAN BE AGGREGATED)
-calculate key metrics of our buisness
-highest level of agg | and lowest level of details USING [agg functions]

5-Magnitude
-compare measures by dims USING [ Group by ]
 

6-Ranking

![image](https://github.com/user-attachments/assets/0d8cfb80-9fc1-4696-adda-1aac5691bd5a)


