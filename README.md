![Banner](https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Revenue_Banner.png)

## Introduction

A computer hardware and peripheral manufacturer company supplies computer support products to different stores around the country. The company allocated a budget to improve sales by doing data analysis on current and historical data. 

## Problem Statement

Get business insigth using data analysis to make better business decisions in the future. One way to mind-map the understanding of this project is to  use Aim's grid. It is a tool that assists in gathering important information about the project for successful project execution.

<p align="center">
  <img width="400" height="500" src="https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Aim's%20Grid.jpg">
</p>

## Database

In this project, the analysis is done on data extracted from MySQL rather than from a data warehouse. In other words, the focus is on online transaction processing (OLTP) not online analytics processing (OLAP). The database is connected to Tableau for visual analysis and dashboard creation.

The database consist of 5 tables : customers, date, markets, products and transactions.

## Data Analysis using MySQL

### How is the sale transactions for 2020 compared to previous years?
In order to answer this question, the tables available in the database have to be joinned together using inner join. As you can see, as the quantity of product sold increases, the total amount of sales increases. However, the quantity of products sold decreased significantly. The total sales dropped by 67% from $6 millions to $2 millions in 2 years!

**2020**

<p align="center">
  <img width="600" height="250" src="https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Inner_join%202020.jpg">
</p>

**2019**

<p align="center">
  <img width="600" height="250" src="https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Inner_join%202019.jpg">
</p>

**2018**

<p align="center">
  <img width="600" height="250" src="https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Inner_join%202018.jpg">
</p>

## Data Analysis using Tableau

Using Tableau we can visualize the above analysis and better understand the significance of the values shown. The trendlines show a negative gradient as the year increases,resulting in lost in revenue.

<p align="center">
  <img width="700" height="350" src="https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Revenue%20Plot%20Tableau.jpg">
</p>

**Dynamic Dashboard showing visualization when 2020 is clicked**

![Dashboard](https://github.com/Hafizah/Revenue-Analysis-using-MySQL-and-Tableau/blob/main/Pictures/Dashboard.jpg)

## Conclusion

A lot more analysis can be done to further understand what kind of product that contributes to declining revenue as well as top products and top customers. The insight from the data will help the sale and marketing team to direct their attention to fix and improve the cost and revenue in the future.




