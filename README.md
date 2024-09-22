# Predicting flight delays using Machine Learning: K-Nearest Neighbors, Naive Bayes Classifier and Random Forest algorithms.

This paper aims to help an airline company improve services and accurately predict flight delays by developing a classification model. The focus is on reducing false positives, where the model wrongly predicts a flight to be on time when it is delayed.

Many delays are preventable with proper planning, and this model can enhance customer experience and scheduling accuracy. By identifying at-risk flights, proactive steps can be taken to minimize disruptions, boosting operational efficiency and customer satisfaction. The ultimate goal is to optimize services, reduce delays, and improve flight reliability.

# Data Overview
The dataset used for both training and testing models have 2201 data points with variables as follow:

1. CRS_DEP_TIME = Scheduled Departure Time
2. CARRIER = Airlines Code
3. DEP_TIME = Actual Departure Time
4. DEST = Airport Code of the Flight Destination
5. DISTANCE = Distance of the flight
6. FL_DATE = Flight Date
7. FL_NUM = FLight Number
8. ORIGIN = Airport Code of the Flight Origin
9. Weather = Weather Code
10. DAY_WEEK = Day of the Week in Number
11. DAY_OF_MONTH = Date in Month
12. TAIL_NUM = Tail Number of the Airlines
13. Flight Status = Real Status of the Flight
14. dep_delay_in_min = Delay in Minutes by Subtracting Actual Departure Time with Scheduled Departure Time. A positive results mean flights departed later than scheduled, and negative results mean flights depart earlier than scheduled
