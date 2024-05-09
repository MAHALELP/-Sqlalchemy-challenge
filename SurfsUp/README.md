Climate Analysis and Flask API Design

Project Overview
This project involves climate analysis and the design of a Flask API for retrieving climate data. The analysis is conducted on a dataset containing weather data for Honolulu, Hawaii. The objectives include exploring precipitation and station data, performing analysis on temperature observations, and creating an API to access this data.

Part 1: Analyze and Explore the Climate Data
Precipitation Analysis
Finding the most recent date in the dataset.
Querying the previous 12 months of precipitation data.
Loading the query results into a Pandas DataFrame and sorting by date.
Plotting the precipitation data and printing summary statistics.
Station Analysis
Calculating the total number of stations in the dataset.
Identifying the most active stations based on observation counts.
Querying temperature data for the most active station.
Plotting temperature observations as a histogram and calculating summary statistics.

Part 2: Design Your Climate App
Flask API Design
Implementing Flask routes for various endpoints:
/: Homepage with available routes.
/api/v1.0/precipitation: Retrieving precipitation data.
/api/v1.0/stations: Retrieving station information.
/api/v1.0/tobs: Retrieving temperature observations.
/api/v1.0/<start> and /api/v1.0/<start>/<end>: Retrieving temperature statistics for specified date ranges.
