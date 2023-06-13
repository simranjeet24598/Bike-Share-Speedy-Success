# ASK

Three questions will guide the future marketing program:
 1. How do annual members and casual riders use Cyclistic bikes differently?
 2. Why would casual riders buy Cyclistic annual memberships?
 3. How can Cyclistic use digital media to influence casual riders to become members?

## Business Statement:
The company’s future success depends on maximizing the number of annual memberships. 
The aim of this project is to help us identify how casual riders and annual members use Cyclistic bikes differently. The results will help us to target the marketing campaign to casual riders to convert them into yearly members. 


## Key Stakeholders:
- Lily Moreno( The director of marketing)
- Marketing Analytics Team(a team of data analysts)
- Cyclistic executive team



# PREPARE
(reliable, original, comprehensive, current or cited)

1. **Reliable** - the data is reliable as the data has been made available by Motivate International    Inc. 
2. **Original**  - The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study, the datasets are appropriate and will enable us to answer the business questions.
3. **Comprehensive** - The data is not comprehensive as the data-privacy issues prohibit us from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.
4. **Current** - The current data available is not efficient in solving the business problem therefore data from the year 2019 is being used here.
5. **Cited** - The data has been made available by Motivate International Inc. under this license






**Description of all data sources used:**

The data is divided into 4 quarters for the year 2019. The data sources used are in the form of CSVs namely:
1. Divvy_Trips_2019_Q1.csv
2. Divvy_Trips_2019_Q2.csv
3. Divvy_Trips_2019_Q3.csv
4. Divvy_Trips_2019_Q4.csv


# Process
1. Documentation of cleaning and manipulation of data:
2. Renamed the columns in the Q2 data source
3. Bind the data of 4 Quarters together
4. Removed duplicate rows
5. Removed null values
6. Removed rows where birthyear is less than 1940 or greater than 2010
7. Added new column “age” and calculated age from birthyear
8. Removed unnecessary column “birthyear”
9. Added new column “day_of_week” and fetched weekday from “start_time” column




# Analyse


**Summary**:

|   |   |Customer  |   |  | Subscriber  |   |
|---|---|---|---|---|---|---|
|  | Count   |Mean Age   |Mean Ride Duration   |Count    |Mean Age   |Mean Ride Duration   |
| Female  |131425   | 30.1  |3157.7   |726428   | 34.1  |965.2   |
| Male  | 212714  | 31.5  | 2691.1  |2187036   |35.8  | 821.8  |
| Total  | 344139  | 30.9  | 2869.3  |2913464   |35.4   | 857.5  |



**Observations:**

*Based on the days of the week*

- Weekday with the most number of rides: Tuesday
- Weekday with the most number of rides by Customers: Saturday
- Weekday with the most number of rides by Subscribers: Tuesday


*Based on month*
- Most Busy months are: Q3 months: June, July, August, September(Summers in Chicago)




**Top three recommendations based on the analysis:**

 1. Offer benefits or discounts for weekends with the annual subscription plan.
 2. Promote riding bikes to work to encourage riders to use bikes on weekdays too.
 3. Encourage and attract more women riders as they have the potential to maximise profits


**_Additional Recommendation_**:
There could be a chance that people do not use bikes on weekdays because their workstations are not in the vicinity of the available bike stations provided by Cyclists or they might not be adequately available. We could use additional data to find out more about this and learn more about the business.






