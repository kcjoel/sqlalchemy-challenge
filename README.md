
# MODULE 10
### SQL Alchemy Challenge

#### Background
This module challenges our knowledge on SqlAlchemy ORM and flask by conducting a trip analysis on a long holiday vacation in Honolulu, Hawaii. This challenge is broken down into two parts with the first being the analyzing and Exploring of Climate Data. The second part is the designing and designating of the climate App. 


#### Instructions
Part 1: Analyze and Explore the Climate Data
  - use the provided files (climate_starter.ipynb and hawaii.sqlite) to complete your climate analysis and data exploration.
  - Use the SQLAlchemy create_engine() function to connect to your SQLite database.
  - Use the SQLAlchemy automap_base() function to reflect your tables into classes, and then save references to the classes named station and measurement.
  - Link Python to the database by creating a SQLAlchemy session.
  - Precipitaion Analysis:
    
    ![image](https://github.com/kcjoel/sqlalchemy-challenge/assets/72319764/15473894-b354-4fd8-a4f3-6262e64e2a90)
    
  - Station Analysis

    ![image](https://github.com/kcjoel/sqlalchemy-challenge/assets/72319764/8df8d812-3429-4878-b003-bfa81dffe442)


 

Part 2: Design Your Climate App
   
1. /

 - Start at the homepage.

 - List all the available routes.

2. /api/v1.0/precipitation

 - Convert the query results from your precipitation analysis (i.e. retrieve only the last 12 months of data) to a dictionary using date as the key and prcp as the value.

 - Return the JSON representation of your dictionary.

3. /api/v1.0/stations

 - Return a JSON list of stations from the dataset.
   
4. /api/v1.0/tobs

 - Query the dates and temperature observations of the most-active station for the previous year of data.

 - Return a JSON list of temperature observations for the previous year.

5. /api/v1.0/<start> and /api/v1.0/<start>/<end>

 - Return a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.

 - For a specified start, calculate TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date.

 - For a specified start date and end date, calculate TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.

   ![sqlalc](https://github.com/kcjoel/sqlalchemy-challenge/assets/72319764/f43dfe98-6613-4b6d-a44e-b8a20333de9e)
