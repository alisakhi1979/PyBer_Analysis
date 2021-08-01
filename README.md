# PyBer_Analysis
## **Overview of Pyber Analysis**

**Purpose:** 
    The purpose of this analysis is to evaluate ride-sharing in diffrent types of cities (i.e. Urban, Suburban and Rural).  

**Objectives:** 
    The overarching objectives and related deliverables for this analysis are the followings:

- Create a dataframe of ride-sharing to examine the following metrics in diffrent city types:
1. Total Rides (quantity)
2. Total Drivers (quantiy)
3. Total Fares (amount in USD)
4. Average Fare per Ride (amount in USD)
5. Average Fare per Driver (amount in USD)

- Create a line graph of ride-sharing data from 01 Jan to 29 Apr 2019 :
1. Weekly trend of total fare earnings in diffrent city types

**Resources:**
1. Data Source: 
- city_data.csv (details of cities and categorizations)
- ride_data.csv (details of rides)
2. Software: 
- Python 3.6.1 (libraries: Pandas and Matplotlib) 
- Jupyter notebook

**Pyber Analysis Results:**
    
1. Ride-sharing dataframe:

The numebr of ride-sharing and drivers are significantly higher in Urban cities (1,625 rides, 2,405 drivers) followed by Suburban cities (625 rides, 490 drivers) and Rural cities (125 rides, 78 drivers). It is worth to note that in all areas the ratio of total rides and number of drivers ( Total Rides/Total Drivers) is higher in Rural cities (1.6) and followed by Suburban cities (1.3) and Urban cities (0.7)

Similiarly the total fares earning is higher in Urban cities (~40K) followed by Suburban (~19K) and Rural (~4K). However, per capita fare earnings are higher in rural cities (34.62 per ride, 55.49 per driver) followed by Suburban cities (30.97 per ride, 39.50 per driver) and Urban cities (24.53 per ride, 16.57 per driver)  


2. Ride-sharing line graph (01 Jan - 29 April 2019):


Fare earnings reached the all time high for all cities in last week of February. Both Urban and SubUrban cities had a higher fare earnings by last week of April than the earning levels at first week of January. Rural cities, however, settled at the same level of earnings at first week of January by closing at last week of April. Overall trend for all cities is increasing earnings from first week of Jan to last week of Feb, declining earnings from last week of Feb continueing to the first two weeks of Mar and thereafter earnings fluactuating up and down by the end of April.   
        
**PyBer Analysis Summary:**

1. The ratio of drivers to rides should be examined to understand the reasons for a high number of drivers in camparison to the number of rides. Hypothetically the inactive profiles might have cuased this odd ratio.
2. The peak of earnings in last week of Feb is important to study and further analysis is necessary. Hypothetically, weather conditions in Feb might have cuased the influx of riders and therefore earnings increased. This hypothesis can be tested by integrating the weather data using OpenWeather API and correlateing the metrics such as wind, rain, tempruture to the number of rides.
3. The over all trend need to be studied to understand that earnings are deman driven or supply driven. In other word, we need to understand the earnings are affected by the availability and accessibilty of the rides or affected by other external elements such as weather conditions or events.      

