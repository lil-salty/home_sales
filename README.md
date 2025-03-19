# home_sales

## Instructions
### Answer the following questions using SparkSQL:
  - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
  - What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
  - What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  - What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

## Requirements
- A Spark DataFrame is created from the dataset. (5 points)
- A temporary table of the original DataFrame is created. (10 points)
- A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. (5 points)
- A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms for each year the home was built. (5 points)
- A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built rounded to two decimal places. (5 points)
- A query is written that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) (10 points)
- A cache of the temporary "home_sales" table is created and validated. (10 points)
- The query from step 6 is run on the cached temporary table, and the run time is computed. (10 points)
- A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. (10 points)
- A temporary table of the parquet data is created. (10 points)
- The query from step 6 is run on the parquet temporary table, and the run time is computed. (10 points)
- The "home_sales" temporary table is uncached and verified. (10 points)

# Sources
Sources for script include: ASU BootCamp Module activities, ASU BootCamp Homework Study Group, Xpert, GitHub, and StackOverflow
