# Technologies Used

<img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/Databricks_Logo.png?raw=true" height="100px">

<img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/spark.png?raw=true" height="100px">

This project is developed using Databricks(https://databricks.com/) and Apache Spark(https://spark.apache.org/)

# Data Attribution

Data used in this analysis is provided by 2U. You can acquire the data using the following links
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/categories.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/customers.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/employee-territories.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/employees.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/order-details.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/orders.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/products.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/regions.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/shippers.csv
  *s3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/suppliers.csv
  *s*3://2u-data-curriculum-team/dataviz-classroom/v1.1/22-big-data/territories.csv


<img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/erd.png?raw=true" height="600px">

# Analysis Performed

* How many orders have been placed in total?  
  Using Aggregation on the orders table we found that there have been 830 orders in total.

* How many orders have been shipped to each country?
  - Germany and USA have had the most oderes shipped(120 orders)
    <img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/shipped.png?raw=true" height="200px">

* For each product, list its product ID, product name, and the company name.

* Which 5 countries have the heaviest shipments, on average?
  Australia, Ireland, USA, Germany, Sweden

    <img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/ship_country.png?raw=true" height="200px">

* Which 10 companies have placed the most orders? List the contact name of each company.
    <img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/customer_contacts.png?raw=true" height="200px">


* Sort customers with a total spending greater than 20,000 in descending order.
    <img src="https://github.com/aarvinrathod/retail_analysis_databricks/blob/main/Images/total_spent_by-customers.png?raw=true" height="200px">

* Sort the employees by the number of orders they sold in descending order.

* How many employees account for about half of the orders?

* List customers who have never placed an order.

* List the products with the highest level of discount in descending order.
