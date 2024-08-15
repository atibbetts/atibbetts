# Project #2

[Boston 311 Level of Service Presentation](/pdf/PPUA_5262_Final_PPT.pdf){:target="_blank"}
<img src="images/wait_times.png?raw=true"/>

### Problem Statement

Between the years 2020 and 2021, there were over 600,000 requests submitted to Boston’s 311 Service. This service records data for each ticket request. The metrics recorded include the case ID, the opened ticket date, the date the ticket was closed, the location information including the neighborhood, census tract, block group, block, and property ID, as well as the ticket type or reason and categories for those ticket types. This information helps a city understand the status of non-emergency issues to alleviate calls to 911 and also help distribute city resources according to current needs. The purpose of this analysis is to uncover any inequities in the level of service being experienced by Boston block groups. Is there a relationship between the wait times of certain 311 tickets and the demographics of different Boston Census Tracts?

MBTA Subway Alert Types
<img src="images/project2tickettypes.png?raw=true"/>

### Urban Informatics Methods

Data from BARI's open data portal was downloaded and processed using R. The duration of time between tickets being opened and closed was calculated and a filter was applied to keep data that was labeled public denigration or private neglect. The most common ticket types with the longest wait times were analyzed further. Linear regression and correlation models were performed on the data using R. Visuals were created in ArcGIS Pro and R. 

Graffit Removal Statistics and Duration Histogram
<img src="images/project2data.png?raw=true"/>

### Urban Policy Implications

The purpose of this analysis was to understand which 311 ticket types had longer wait times and of those ticket types, were there disparities in the wait times experiences across different census tracts. The results of this analysis can highlight some of the bigger problems faced in the city and where they are occuring. Some of the tickets called in to the 311 service are chronic issues. Understanding where these issues exist and which neighborhoods are affected most can inform decisions and resource allocation in the city to alleviate the issues and provide more equitable service.

There is more to level of service than just comparing wait times between block groups. Customer service is an important metric for the department in charge of running the service to understand what the needs of the city are, where the different issues exist or persist over time, how needs change over time, and how well the city performs at meeting those needs. The data describing service levels and performance can also be used to hold different city departments accountable for addressing different issues in a more timely manner than before the data was available. With improved accountability, resident satisfaction with the 311 service would then be expected to improve as well. Using CRM (customer relationship management), cities can begin to monitor, measure, and analyze services at the city or departmental level so city managers can know for  certain whether they are hitting service-level targets.

Service Alert Counts by Station Map
<img src="images/project2rodentmap.png?raw=true"/>