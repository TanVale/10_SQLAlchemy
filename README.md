# 10_SQLAlchemy
In this challenge I have -
- Used Python and SQLAlchemy to do a basic climate analysis and data exploration of the climate database.
- Used the SQLAlchemy create_engine() function to connect to SQLite database.
- Used the SQLAlchemy automap_base() function to reflect tables into classes, and then save references to the classes named station and measurement.
- Link Python to the database by creating a SQLAlchemy session.
- Performed a precipitation analysis and then a station analysis by completing the steps in the following two subsections.

Precipitation Analysis
 - Found the most recent date in the dataset.
 - Using that date, got the previous 12 months of precipitation data by querying the previous 12 months of data
 - Loaded the query results into a Pandas DataFrame. Explicitly set the column names.
 - Sorted the DataFrame values by "date".
 - Plotted the results by using the DataFrame plot method.

Station Analysis
- Designed a query to calculate the total number of stations in the dataset.
- Designed a query to find the most-active stations (that is, the stations that have the most rows).
- Plotted the results as a histogram with bins=12.
- Closed session.
