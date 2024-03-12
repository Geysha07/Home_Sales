# Module 22 Challenge: Home_Sales
For this challenge, we used our knowledge of SparkSQL in order to measure key metrics about home sales data. We created temporary views, cached and uncached data, partitioned the data and compared the runtime of cached vs uncached table queries as well as the runtime of cached tables vs parquet table queries. In the end, we also had to verify that the table was uncached. Here are some of the questions that we answered using SparkSQL:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
