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
## Data Analysis and Insights 
Matplotlib and different Seaborn visualization plots were used to examine relationships and explore the data.
The following insights were obtained:
* Lagos state had the highest number of cases
* The highest daily confirmed cases (6158) was recorded on the 22nd of December, 2021
* The highest daily recovered cases (29084) was recorded on the 3rd of December, 2020
* There were more confirmed cases and COVID-19 deaths in areas with high population density and epidemiological index
* There were more confirmed cases and COVID-19 deaths in areas with low socio-economic index and transport availability
* GDP was highest in the fourth quarter of 2019
* The budget of Cross River state was the most affected by the COVID-19 with a budget reduction of about 950 billion naira, followed by Lagos state with a budget reduction of about 650 billion naira.
