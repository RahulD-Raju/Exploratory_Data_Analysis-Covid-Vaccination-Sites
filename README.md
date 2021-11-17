# Exploratory Data Analysis/NYC-MTA Covid Vaccination Site Placement

Prepared by Rahul D. Raju

## 1.  PROJECT OVERVIEW
The purpose of this project was to advise the NYC Department of Health on how it could best employ the NYC subway system as a vaccine distrubution mechanism.
An analysis was conducted of passenger traffic for the months spanning Febuary/2021 to June/2021 and the daily turnstiles entries occuring between 4PM to 8PM.  Various Exploratory Data Analysis methods were employed.
The top 5 stations by foot traffic were eventually choosen.  Also, ith close to 25% of NYC's workforce compromised of out of city/state workers, a focus was placed on major transportation hubs. Finally,
New York City currently has a 49% vaccination rate(fully), well below the 70% required for herd immunity.  As such, neighborhoods with low vaccination rates were surveyed for high traffic stations.  

## 2.  DATA SOURCES
- MTA subway station data: http://web.mta.info/developers/turnstile.html
- MTA data key: http://web.mta.info/developers/resources/nyct/turnstile/ts_Field_Description.tx
- Custom Google Maps: https://www.google.com/maps/@40.7203674,-73.9947657,12z/data=!3m1!4b1!4m2!6m1!1s1CtQ5TfKwMj8Wvk3P25zSs5kjFRcnR2ID
- NYC Department of Health:  https://www1.nyc.gov/site/doh/covid/covid-19-data-vaccines.page

## 3.  BASIC METHODOLOGY
- The Project Workflow were as follows:
   -  Download of MTA datasets
   -  Selection of time frame of data for analysis
      -  A total of the three most recent months was choses
      -  A daily time period between 4pm - 8pm was chosen as commuters are more likely to recieve the vaccine
         on the way home from work versus the way to work
   -  Data was cleaned, with a focus on duplicates and incorrect station entry data
   -  Visualize data by station, turnstile and passenger traffic
   -  Station data was also manually cross-referenced with low vaccination rate neighborhoods
   
 ## 4.  RESULTS SUMMARY
 A total of 10 stations were chosen based on various criteria
     - Stations with highest foot traffic during selected dates and chosen daily hourly time-frame
       - 34-St Herald Square
       - 42-St Grand Central
       - 42-St Port Authority
       - Flushing-St Main
       - 34-St Penn
       
     - Stations that serve as conduits for out of state/city workers, as expected they are mostly the same as highest overall foot traffic stations
       - 34-St Herald Square
       - 42-St Grand Central
       - 42-St Port Authority
       - 34-St Penn
       
     - Top Station in the 5 lowest vaccinated neighborhoods(adjusted for population size)
       -  Canarsie:  Rockaway Av
       -  Borough Park:  Avenue 1
       -  Cypress Hills/E. NY:  Euclid Av
       -  Midwood:  Kings Highway
       -  Claremont/Morrisania:  167 St
       
   ## 5.  TOOLS and TECHNIQUES USED
       - [Jupyter](https://jupyter.org/)
       - [Pandas](https://pandas.pydata.org/)
       - [Numpy](https://numpy.org/)
       - [Matplotlib](https://matplotlib.org/)
       - [Seaborn](https://seaborn.pydata.org/index.html)
       
       
       
 
 
