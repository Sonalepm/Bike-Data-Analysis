Communicate Bike Trip Data Findings
-----------------------------------------

The goal of this project is to wrangle, analyze and visualize data.

Table of Contents
Introduction
Part I - Gathering Data
Part II - Accessing Data - Visual and Programatic
Part III - Cleaning Data
Part IV - Storing Data
Part V - Analyzing and Visualizing Data
  - [Univariate Analysis]
  - [Bivariate Analysis]
  - [Multivariate Analysis]
Part VI - Conclusion

Introduction:

The data set includes information about individual rides made between 2017 and 2019 in a bike-sharing system covering the greater San Francisco Bay area. The bike sharing system is provided by Bay Wheels under Lyft. Bay Wheels trip history data was downloaded from the below url:

https://s3.amazonaws.com/baywheels-data/index.html

Each trip data includes various details like

Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
member_birth_year
member_gender

Various univariate,bi-variate and multivariate analysis will be performed on the data. Both fordgobike and baywheel data is used for the analysis


Conclusions:
1) 82% of the bike trips are made by Subscribers.
2) The average trip duration is around 15 mins.
3) Most trips are made during weekdays than weekends.
4) Usually Customers take longer trip_duration than Subscribers.
5) The trip duration of Customers has a decreasing trend from January to December, whereas the trip duration remains stable for Subscribers.
6) Male Subscribers made the most number of trip from 2017 to 2019.
7) Bike Share For All program is not very popular as there are only very few Subscribers who make use of the  program. 

References:
https://seaborn.pydata.org/tutorial.html
https://matplotlib.org/3.2.1/gallery/lines_bars_and_markers/categorical_variables.html
https://stackoverflow.com/questions/20906474/import-multiple-csv-files-into-pandas-and-concatenate-into-one-dataframe
https://botbark.com/2019/12/18/how-to-disable-warnings-in-python-and-pandas/

