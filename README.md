Assignment 23 _ Big Data - Home-Sales-with-PySpark-SQL
Through utilizing PySpark and Spark SQL on Google Colab, this project serves to determine key metrics about home sales data. Then, Spark is utilized to create temporary views, 
partition the data, cache and uncache a temporary table. Some of the data key metric questions that were answered:

     1.What is the average price for a four-bedroom house sold for each year?

     2.What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?

    3.What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

    4.What is the "view" rating for homes costing more than or equal to $350,000?

    Create Spark Session

    ![image](https://github.com/AJosephrajan/Home_Sales/assets/146452567/a6aaf974-b12b-477b-b747-74c9a5a4ef88)
 After Creating Spark Session The above questions Were answered and the runtime has been calculated before and after partion the data. 
 Example
 Using the cached Data
 ![image](https://github.com/AJosephrajan/Home_Sales/assets/146452567/fdd580b7-d351-4a6f-8964-50bf56d5c5b1)

 Using the parquet DataFrame
 ![image](https://github.com/AJosephrajan/Home_Sales/assets/146452567/38d8bf02-ec31-4de8-bced-9f54b1853c59)

 
