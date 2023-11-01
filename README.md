# Used-cars-Time-Series-Project
My Strategy:
-First, I dealt with the dataset's missing values. I fixed this by filling in the missing values on the corresponding columns with the median and mode of numerical and categorical data.


The data types of the columns in the dataset were then transformed to the appropriate data types, and the posting_date column was converted to a datetime data type.

I then utilized the posting_date column to generate a datetime index for the dataset, allowing me to readily evaluate the data's temporal patterns.

Once I had clean data, I investigated it with various visualizations and statistical analysis methods. This stage allowed me to examine temporal patterns, seasonal trends, and demand-supply dynamics by location and vehicle type. Finally, after gaining a thorough knowledge of the data, I constructed the time-series charts.


In the last analysis, after successfully handling missing values and cleaning the data, I will move on to the next step, where I will aggregate the data based on the "posting_date," "region," and "type" of the vehicle to be able to analyze the temporal patterns, seasonal trends, and demand-supply dynamics.
This will allow me to perform various analyses and gain insights into how the inventory varies over time in different regions and vehicle types
