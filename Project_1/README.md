![](https://qtxasset.com/cdn-cgi/image/w=850,h=478,f=auto,fit=crop,g=0.5x0.5/https://qtxasset.com/quartz/qcloud4/media/image/2020-12/SingapoReimagine_Apple%20Marina%20Bay%20Sands.jpg?VersionId=UqdPVqyUr5TD_ADenVwkmZTmj64CoL2q)
# Project 1: Exploring climate data of Singapore

### Executive Summary

Singapore tourist arrivals had fell by 85% to 2.7m, lowest in four decades due to Covid-19. Tourism contributes to Singapore GDP yearly at around 4% and the Covid-19 has caused tourism reciepts to become almost zero GDP contribution in 2021. The loss in visitor arrivals has direct and indirectly affects many industry. Some of the sections affected will be travel services, accomodation, transportation, recreation activities and F&B services. Many people loss their job or income as a result. This project aims to analyse trends in Singapore weather and visitor arrivals to identify how rainfall affects visitor arrivals. This analysis can help leverage monsoon data and visitors’ arrival data in deciding when is best to organize strategic tourism events to boost Singapore’s tourism arrivals. We believe that having the right strategic tourism event in the right time will bring in the right visitors. 


### Problem statement

There had been a huge drop in visitor arrivals due to covid and this result in leser tourism receipts for our GDP. This analysis can help leverage monsoon data and visitors’ arrival data in deciding when is best to organize strategic tourism events to boost Singapore’s tourism arrivals.

### Methodology 
We will be using data from 1996 to 2015 only, this is a good representation of the trends. 2020 onwards the tourist data are no longer relevant due to Covid restriction for leisure travellers, we are only missing fours years data 2016,2017,2018,2019. 
- rainfall_monthly_total
- rainfall_monthly_number_rain_days
- total_visitor_international_arrivals_monthly
- visitor-international-arrivals-to-singapore-by-country-monthly

### Data dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**total_rainfall**|*float*|rainfall-monthly-total|Total rainfall in mm| 
|**no_of_rainy_days**|*float*|rainfall-monthly-number-of-rain-days|number of rainy days per month| 
|**total_international_visitor_arrivals**|*float*|total-visitor-international-arrivals-monthly|total international visitors arrivals per month|
|**region**|*integer*|visitor-international-arrivals-to-singapore-by-country-monthly|which continent the coutry belongs to|
|**country**|*integer*|visitor-international-arrivals-to-singapore-by-country-monthly|this includes the name of each country and also the group ASEAN is inside as well|
|**no_of_visitor_arrivals**|*float*|visitor-international-arrivals-to-singapore-by-country-monthly|total visitors arrivals based ont he country in the row per month|

### Brief summary of your analysis
- September is the lowest visitor arrivals monthly mean
- There are heavier rainfalls in December and January.
- July, August and December has more visitors arrival
- The top five countries visiting arrivals are Indonesia, China, Australia, Japan, Malaysia
- Most number of visits happen during Northeast Monsoon (Dec-Feb) and Southwest Monsoon season (Jun-Sept).Throughout the seasons, Indonesians remain the highest visitors, followed by Chinese tourists.There are more Japanese and Australian visitors during Southwest Monsoon season (compared to their visits during the rest of the year)

### Conclusions/recommendations

Our strategy is to curate the right strategic tourism events for the right visitors’ 
during the right period. 

We recommend the below activites:

Jun - Sept : Eat and Shop in Sunny Singapore
Guinness World Record for Longest Satay Line
Singapore Food Trails 
Great Singapore Sales 

Dec - Feb : An Event for Everyone
indoor Musical, circus and carnivals
Indoor snow experience with family
Christmas Wonderland at Gardens by the Bay
Party events


Potential enhancements

The current data set only shows visitors arrivals, and not spending
Not all visitors are big spenders
Spending gives a better idea on which country’s tourists are giving the most return 
To assign weightage to countries
based on proximity of their countries to Singapore

### Citation

F1 to Help Boost Singapore Tourism 2008 (Retrieved from https://www.dw.com/en/f1-to-help-boost-singapore-tourism/a-5213161)

S’pore’s tourist arrivals fell 85% to 2.7m, lowest in four decades due to Covid-19 2021 (Retreived from https://www.straitstimes.com/singapore/consumer/27-million-visitors-in-singapore-in-2020-lowest-in-four-decades-due-to-covid-19)

COVID-19’s Economic Impact on Tourism in Singapore 2021 (Retreived from https://www.iseas.edu.sg/wp-content/uploads/2021/07/ISEAS_Perspective_2021_108.pdf)
