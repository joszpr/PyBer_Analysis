# PyBer_Analysis

## **Overview** ##

##### **Background** ##### 

Analysis performed on PyBer ride sharing data for 2019. The analyzed data contains rides done in different cities through the United States and includes the date the ride took place, the fare for the trip, the city location for the trip, the type of location the city is classified as (Urban, Suburban or Rural) and the amount of drivers that were available in that city when the ride was initiated. The evaluation of the data was done in order to provide insights about trends and patterns that could facilitate strategic decisions for the company. 

##### **Methodology** #####

The data was obtained from two CSV files. One contained information of driver counts for individual cities along with the type of city. The other file contained information for specifics rides done along with their dates, fare amount and city. The data was merged utilizing Jupyter Notebook with Python as programming language. Statistical analysis per performed on the data in order to provide insights of possible patterns or trends. The analysis generated charts that allows effortless understanding of the data.  

## **Results** ##
##### **Data Description** #####

![Sample of Data](https://user-images.githubusercontent.com/85839235/127438713-1ea06871-436a-4a45-a753-953f19ff9cc0.png)
Snippet of the data source that shows the information being analyzed. 

![Fig1](https://user-images.githubusercontent.com/85839235/127438737-fe969445-bebd-4db4-b8ca-a801311ae9ab.png)
Scatterplot created by filtering the data by Average Fare per Riders and categorized by City type.  

##### **Observations** #####
-	Most of the rides taken from PyBer customers were done in Urban areas. With the least number of rides performed on Rural areas. 
-	The average fares cost were the highest on Rural areas. The Urban cities showed lower average of fare amounts. 
-	There is considerably fewer number of drivers in the Rural areas. The Urban cities have significantly higher number of drivers. 
-	Suburban areas have consistent results in all metrics. 

##### **Statistics** #####

![Fig2](https://user-images.githubusercontent.com/85839235/127438780-50a0167c-56bb-498c-a885-d8dfe09676da.png)

Box-and-whisker that represents the number of Rides by City types. 
-	It confirms the insights of the Scatterplot regarding the considerably higher number of rides taken in urban cities. Urban cities have the only outlier in the dataset. 
-	The median value for Rural cities is skewed low in its data.

![Fig4](https://user-images.githubusercontent.com/85839235/127438801-f0a6a25a-ea61-4340-b6c2-ebbbb6fa27da.png)

Box-and-whisker that represents the number of Drivers by City types. 
-	It confirms the difference in amount of drivers by city type observe in the Scatterplot. 

![Fig3](https://user-images.githubusercontent.com/85839235/127438811-10439e49-e237-4d42-84f2-afa07c46f7cd.png)

Box-and-whisker that represents the cost of Fares by City types. 
-	The fare cost for rides is shows the least amount of variance compared to the previous 2 metrics but it still shows a higher cost per ride in Rural areas. 

##### **Material for Presentation** #####
Comparison of the data by percentage of Total Rides, percentage for the Amount of Drivers and Percentage of Fares by city. 

![Fig6](https://user-images.githubusercontent.com/85839235/127438837-415afbda-8d45-437d-93ac-f9cbeb1f498a.png)

![Fig7](https://user-images.githubusercontent.com/85839235/127438849-8608b966-265d-4e05-bd18-233e854c3c49.png)

![Fig5](https://user-images.githubusercontent.com/85839235/127438861-ce93240e-1dc2-429b-a911-df65d2d8c602.png)

## **Summary** ##

![PyBer_fare_summary](https://user-images.githubusercontent.com/85839235/127438886-ed03c043-c52d-4be2-949d-2b6eb3979f51.png)
The data was processed in order to represent the patterns of orders by City type and the Fare amount along the first 4 months of 2019 with data boxed on a weekly basis. 

- **Income per City** - The average Fare amount is lower in Urban areas compared to Suburban and Rural but they represent the majority of income for the company month after month. 

-	**Seasonality** - While there are changes in demand around March for all three types of cities, the Urban cities illustrates more frequent changes in demand while Suburban show the highest shift periods. 

-	**Rural Profitability** - The income per Fare for Rural areas is high and lower number of Drivers. That relation results in the lowest profitability from all the city types. 

#### **Conclusions and Recommendations** ####
-	Further research is recommended in order to gather more data around Rural areas and the possibility to increase the customer base. The low number of Drives in Rural areas could be the result of high costs for trips because of the lower availability of Drivers. Customer may be pushed away from using PyBear due to high cost for drives. A campaign to increase the number of drivers could be useful to identify if more customer adopt PyBer in Rural areas. 

-	A temporary promotion for Rural areas could be useful to identify if there is more demand that is not being met due to lack of knowledge regarding the platform.

-	Suburban cities show a close relation to Urban cities in regard to Ride counts along with similar Fare average cost while they have a big difference in amount of drivers. There may be potential to increase profitability in Suburban areas if more Drivers are attracted to PyBear and current drivers incentivized to take more trips. 

-	Targeted promotions to incentivize the use of the apps in Urban cities on periods where demand patterns seem to be lower throughout the year.  Pair promotions with knowledge of Cities local events in order to incentivize use of the app when demand for the services is projected to be lower. 
