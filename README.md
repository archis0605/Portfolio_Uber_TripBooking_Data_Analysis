# Portfolio_Uber_TripBooking_Data_Analysis
Set of real world dataset tasks is completed by using the Python, Pandas, Seaborn, and Matplotlib library.


## Background Information:
In this porfolio we use Python Pandas, Seaborn, and Matplotlib to analyze and answer business questions about trips booked through Uber platform. The data contains hundreds of thousands of raw data on Uber pickups in New York City from April to September 2014. The files are separated by month and each has the following columns:

- Date/Time: The date and time of the Uber pickup.
- Lat: The latitude of the Uber pickup.
- Lon: The longitude of the Uber pickup.
- Base: The TLC base company code is affiliated with the Uber pickup.


We start by cleaning our data. Tasks during this section include:

- Conversion of 'Date/Time' column from string to datetime format
- Split the 'Date/Time' column and Add 6 columns (i.e. Month, Day, Year, Hour, Minute, Second)
- Add 'DayofWeek' column into the table


Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 6 high level business questions related to our data:

1. What are the peak hours for Uber rides in NYC during 2014?
2. What is the highest number of trips booked on weekdays?
3. In which month the highest number of trips were booked?
4. On which date of the month, was the largest number of trips reserved and why?
5. Find the correlation between Weekdays and Month?
6. Which portion of the NYC most uber trips were reserved by plotting a map?


To answer these questions we walk through many different numpy, pandas, seaborn, and matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Conversion from string to datetime column
- Split the existing and Adding the columns obtained from the existing columns
- Plotting bar charts, correlation chart, and scatter plots to visualize our results
- Labeling our graphs
