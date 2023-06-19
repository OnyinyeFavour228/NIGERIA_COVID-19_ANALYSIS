# Nigeria COVID-19 Analysis
![COVID-19 Image](https://github.com/OnyinyeFavour228/Nigeria_COVID-19_Data_Analysis/assets/107655675/9e417336-dda6-4392-bf7e-f1a77d55b2e4)
COVID-19 is an infectious disease caused by Corona virus. It affected major parts of the world including Nigeria. After Nigeria recorded its first case on the 27th of February, 2020; several activities in the country were affected as lockdown & curfews were observed and major airports were shut down.
This is an analysis of the effects of COVID-19 in Nigeria. Python was used to collect data, perform analysis and create visualization.
## Data Sourcing 
* I extracted COVID-19 data across all the 37 states in Nigeria from NCDC website using web scraping with Python.
* I imported Global COVID-19 daily data on confirmed cases, death and recovered cases from Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) github repository.
* Ustacky provided me with the following datasets:
  + Vulnerability Index data for the 37 states in Nigeria
  + Nigeria GDP for each quarter of the year from 2014 to 2020
  + Budget data for each state in Nigeria.
## Data Cleaning / Transformation 
The following steps were taken to clean and transform the data.
* Extracted the daily data for Nigeria from the global COVID-19 daily data using the loc function in Pandas.
* Converted the columns in the Nigeria COVID-19 daily data to their appropriate data type.
* Used Pandas diff method to return Nigeria COVID-19 daily new cases.
* Log transformed the total cases columns to reduce the skewness.
* Changed the data frame format of the Budget and GDP data using Pandas melt function to enable a more comprehensive plot.
