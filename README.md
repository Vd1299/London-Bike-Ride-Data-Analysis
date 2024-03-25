# London-Bike-Ride-Data-Analysis
The repository contains details about data processing and cleaning using Pandas for london Bike riding dataset, as well as the analysis and visualization of data using Tableau.

Dataset was retrieved from Kaggle.
Data Manipulation was done using Pandas library of Python. It contains some basic manipulation to streamline the dataset for Data Analysis Purpose.
Data Visualization was done in Tableau along with analysis of data.

Features:
1.	Time Stamp: Provides time stamp.
2.	Count of Riders: Number of riders at that time.
3.	Real Temperature: Temperature in degree Celsius.
4.	Feels like Temperature: Feels like temperature in degrees Celsius.
5.	Humidity Percent: Percent of humidity.
6.	Wind Speed: Wind Speed in KPH.
7.	Weather: Weather status.
8.	Holiday: Indicates whether that day was holiday or not (0, 1).
9.	Weekend: Indicates whether that day was weekend or not (0,1).
10.	Season: Indicates the season.

Transformations: Done using Python
1.	Creation of Primary key: Create a primary key to identify each row uniquely. 
2.	Column renaming: Rename the columns appropriately.
3.	Data Cleaning and removal of Null values.
4.	Data Type Conversions: Converted appropriate columns to their respective data types.
5.	Data Transformation: Transformed numerical categorical data of weather, season text data types.
6.	Conversion of humidity: Converted humidity to appropriate decimal places.
7.	Export the transformed data into csv file.

Key Findings:
•	Seasonality: Analysis reveals fluctuations in bike ride counts across different seasons, with increased usage during Clear weather conditions, followed by Scattered cloudy weather.
•	Weather Impact: There is a noticeable correlation between temperature, wind speed, and bike ride counts, indicating that weather conditions significantly influence rider behavior. The most favorable temperature and wind speed for bike rides was 14.6 degrees and 13.7 KPH.
•	Holiday and Weekend Effect: Further investigation into the impact of holidays and weekends on bike usage patterns provided valuable insights for urban planning and transportation management indicating increased in number of rides on weekends and holidays.
•	Total bike rides: The total number of bike rides done in given period of data is 19905972.
