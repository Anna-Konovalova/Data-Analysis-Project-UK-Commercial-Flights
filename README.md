# Data Analysis Project 

UK Commercial Flights: pre- and post-pandemic
======

Project Overview
------
To prevent the spread of the COVID-19 pandemic, countries around the world have taken a variety of restrictive measures since the beginning of 2020. Due to these restrictions, the air transport industry suffered a blow – but the most recent figures on commercial flights show signs of recovery.

In this prjoject, I analysed commercial flights in the United Kingdom before and after Covid-19 pandemic. More specifically, the focus of my data analysis was to answer the following questions:
1. How does the number of flight departures compare pre- and post-pandemic in the UK?
2. How has the UK recovered from Covid-19 compared to other major European countries?
3. Have the top busiest UK airports gone back to pre-pandemic levels?
4. How do post-pandemic flight departure delays compare to pre-pandemic levels in the UK?


Tech
------
The whole project was completed in Python. For data validation and data wrangling I used Pandas and NumPy. For data visualisation I used Matplotlib and Seaborn.  


Data
------
The data I used for this project comes from [Eurocontrol](https://ansperformance.eu/data/) - a pan-European, civil-military organisation dedicated to supporting European aviation. Data on commercial flights include scheduled and non-scheduled commercial flights (passengers, freight and mail) performed under Instrument Flight Rules (IFR).

I have used two datasets: *flights.csv* and *delays.csv*. 

*flights.csv* contains raw data on daily IFR arrivals and departures by airport for the period January 2016 - September 2022. 

*delays.csv* contains raw data on total daily pre-departure delays by airport for the period January 2016 - August 2022.

<img width="849" alt="Screenshot 2022-11-14 at 15 30 48" src="https://user-images.githubusercontent.com/78367070/201699925-3ff408cc-4794-4aca-8f6f-b42a057d3298.png">

Data Analysis Summary
------
### 1. How does the number of flight departures compare before and after the pandemic in the UK?
&nbsp;  


![data_vis_1](https://user-images.githubusercontent.com/78367070/201700954-a6f1c240-8d45-4bc5-86ef-a38c105dcda0.png)


&nbsp;  

* As expected, flight departures in the UK dropped significantly when COVID-19 pandemic began.
* In the two years since the beginning of the pandemic, 62% less flights departed compared to the last two years before the pandemic.
* In the third quarter of 2022 flight departures are still not at pre-pandemic levels.


&nbsp;  

### 2. How has the UK recovered from Covid-19 compared to other major European countries?
&nbsp;  


![data_vis_2](https://user-images.githubusercontent.com/78367070/201701264-0ddc0cb4-3c7b-4261-80dd-f335838a4801.png)


&nbsp;  

* Comparing current average daily departures, to those in 2019, the UK has had a worse recovery than Italy, Spain and France. The average daily departures currently make up 78% of 2019 average for the UK, compared to 90%, 93% and 90% for Italy, Spain and France respectively. 
* The UK has had a better recovery than Germany - 78% for the UK compared to 71% for Germany.


&nbsp;  

### 3. Have the top busiest UK airports gone back to pre-pandemic levels?
&nbsp;  


![data_vis_3](https://user-images.githubusercontent.com/78367070/201701554-391b9023-4b5c-4147-ba94-31f809600a96.png)


&nbsp;  

* All of the top busiest airports in the UK do not have the same number of departures that they had before the pandemic.
* Airports where flight departures are the closest to pre-pandemic levels are London Stansted, followed by East Midlands, London Luton, London Gatwick and Manchester. 
* The worst recovery in terms of flight departure numbers is experienced by London City airport.


&nbsp;  

### 4. How do post-pandemic flight departure delays compare to pre-pandemic levels in the UK?
&nbsp;  


![data_vis_4](https://user-images.githubusercontent.com/78367070/201701813-f458158f-1da4-4b64-93be-c71e4c406019.png)


&nbsp;  

* Although UK airports have experienced a number of issues getting back on track after COVID-19 pandemic, almost all airports (apart from London Heathrow) still had a slightly lower proportion flights delayed in 2022 compared to 2019. 


