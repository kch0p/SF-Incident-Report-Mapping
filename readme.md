
# San Francisco Crime: Descriptive Statistics and Geographic Visualization

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

This was one of the main problem sets for the Legal Studies 123 Course at UC Berkeley. We used publicly available crimes/geolocation data from the city of San Francisco to conduct an exploratory 
data analysis (EDA) using Python3 and [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide), as well as create static and time-based crime maps using [Plotly](https://plotly.com/python/), [GeoPandas](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.html#geopandas.GeoDataFrame), and [GeoJSON](https://geojson.org/). Data was sourced 
from the years 2018-2021, as well as pre-made neighborhood boundary map files.

Project code (and more detailed discussion) available upon request. This is mostly to respect the course's 
academic integrity and future students working with the data.


### Example EDA & Descriptive Statistics: 
*Is there a relationship between day of week, time, and whether an incident occurs?*

Interestingly, there wasn't much of a difference in day-to-day 
activity as there was in time of day activity. To answer this, 
I properly formatted the existing [datetime](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html) data, 
and then grouped by *hour of the day* and *day of the week* to see if there were any major differences. 

![App Screenshot](https://github.com/kch0p/Legal-Studies-123-Problem-Set-1/blob/main/readme_files/images/hour_of_day_chart.png

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



*Check to see if crime rates over time change when looking at particular types of crime. Plot and explain your findings.*
Most notably, almost all crimes saw significant declines at the beginning of the COVID-19 Pandemic in February of 2020. What was interisting however
was how some crimes bounced back, while others have stayed much lower since. 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


*What neighborhoods experience the most crime? Do different neighborhoods experience different types of crimes at different rates, or is the distribution of crime spatially consistent across neighborhoods?*


Central, Northern District, and the Mission all had the highest overall amounts of crime. By further calculating proportions of top 10 crimes per district however, 
I was also able to find that different neighborhoods experienced certain crimes at *very* different rates. While it wasn't
explicitly required, I created a secondary table to further visualize what neighborhoods
experienced high crime rates in what categories. 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


### Example Maps 


