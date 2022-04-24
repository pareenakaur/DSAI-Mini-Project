# DSAI-Mini-Project

Dataset = https://www.kaggle.com/datasets/akshay4/road-accidents-incidence

## About

This is a Mini-Project for SC1015(Introduction to Data Science and Artificial Intelligence) which focuses on Road Accidents Incidence. For detailed walkthrough, please view the source code in order from:
1. ReadMe file
2. Numerical
3. Categorical

## Description of topic and problem

Problem- How can we accurately predict the severity of traffic accidents (using geographical area, human factors, environmental conditions, vehicle conditions)? How can we effectively lower the severity of traffic accidents?

Motivation for our project stems into three main ideas:
1. It is a common problem and issue worldwide. Every year, nearly 1.35 million people die in car accidents. Furthermore, such accidents place a huge burden on the economic and healthcare aspect of the country.
2. Trend of increasing road accidents globally, although proven to decrease during lockdown period where there is constraint of movement.
3. We can explore ways in which we can mitigate the problem and dive in deeper into ways in which we can reduce the severity or occurence of such accidents. Such examples include speed and environmental conditions.

These reasons suggests the importance that this issue holds at hand it why it is a more pressing issue in today's present context. These reasons motivated us to want to try to look further regarding road accidents and to try and reduce the costs and damage done to humans, as well as for the country. 

## Models used
1. Linear Regression
2. Logistic Regression
3. Random Forest Classifier

## Conclusion
Conclusion on main topic:
We can accurately predict severity of accidents using speed limits, types of junctions and geographical factors(urban or rural area).
We can effectively improve severity of accidents through:
1. Implementing Short-term Plans: Having more stringent policies that sets lower speed limits and heftier fines
2. Implementing Long-term Plans: 
(a) By having better infrastructure planning to modify and improve the structure of T or staggered junctions and implementing more support structures such as road-side mirrors and surveillance cameras.
(b) Using education as a tool to educate public on safe speed

Data-Related Insights:
1. Resampling imbalanced data using undersampling and oversampling helps improve model performance 
3. Using Tree nodes to represent data may not be appropriate for all types of data
4. There are some factors in which we can look into to mitigate the severity of accidents, however they are not explicitely shown in the dataset

## What did we learn from this project?
1. Meaningful problem formulation and data selection 
2. Handling imbalanced data using imblearn package
3. Implementing different types of new models (Logistic Regression and Random Forest Classifier from sklearn) to provide better comparison between variables
4. Intepreting 3-by-3 Confusion Matrices
5. Concepts about Precision, Recall, and Classification Accuracy Scores
6. collaborating using github


## Classification of Variables
### Numeric data
- Number of Vehicles: Number of vehicles involved in the accident
- Number of Casualties: Number of casualties involved in the accident
- Location Easting OSGR (Null if not known): Location on a projected coordinated system with reference to the east
- Location Northing OSGR (Null if not known): Location on a projected coordinated system with reference to the north
- Longitude (Null if not known): Angular distance of a place east or west of the greenwich meridian
- Latitude (Null if not known): Angular distance of a place north or south of the greenwich meridian
- Speed limit: Speed limit at that particular road 
- Age of Driver: Age of the person using the vehicle (involved in the accident)
- Engine Capacity: Measurement of the total volume of the cylinders in the engine
- Age of Vehicle (manufacture): Age from which the vehicle was first manufactured or created
- Age of Casualty: Age of the person injured or killed in an accident (the victim)


### Categorical data
- Police Force: Presence of the police force at the accident site
- Accident Severity: How severe the accident is, usually referring to the consequences and damage done
- Local Authority (District): administrative body in local government (subnational division)
- Local Authority (Highway Authority - ONS code): administrative body in local government (in charge of the highway)
- 1st Road Class: The different types of class that the road belongs in
- Road Type: The road type that the road belongs in
- Junction Detail: detail of the road junction in which the accident was involved
- Junction Control: control of the road junction in which the accident was involved
- 2nd Road Class: The different types of class that the road belongs in (roads forming primary transport network)
- Pedestrian Crossing-Human Control: Presence of human control at pedestrain crossing
- Pedestrian Crossing-Physical Facilities: Presence of facilities that aid in pedestrain crossing
- Light Conditions: How bright the area of accident is
- Weather Conditions: How extreme the weather conditions at area of accident is
- Road Surface Conditions: How extreme the road surface is (unsteady, rocky path etc)
- Special Conditions at Site: Presence of anything special at the accident site
- Carriageway Hazards: Presence of carriageway hazards at site of accident
- Urban or Rural Area: Whether the accident took place at a urban or rural area
- Did Police Officer Attend Scene of Accident: Presence of police officer at accident site
- Vehicle Type: Type of vehicle involved in accident
- Towing and Articulation: Whether towing and articulation was needed at the accident site
- Vehicle Manoeuvre: The need to manoeuvre the vehicle (turning, changing lanes, slowing down, leaving the road etc)
- Vehicle Location-Restricted Lane: Whether the vehicle was located at a restricted lane
- Junction Location: Location of junction
- Skidding and Overturning: Presence of skidding or overturning during accident
- Hit Object in Carriageway: Whether an object was hit in the carriageway-road meant for vehicles
- Vehicle Leaving Carriageway: Whether vehicle left the carriageway-road meant for vehicles
- Hit Object off Carriageway: Whether an object was hit off the carriageway-road meant for vehicles
- 1st Point of Impact: When the first point of impact took place
- Was Vehicle Left Hand Drive: Whether vehicle was manufactured for left-hand drivers
- Journey Purpose of Driver: Purpose of the driver to use the vehicle
- Sex of Driver: Sex of the person using the vehicle
- Age Band of Driver: Age range of the driver
- Vehicle Propulsion Code: Different codes given to different propulsion type of the vehicle
- Driver IMD Decile: Dimension which places the deprivation scores of individual areas 
- Driver Home Area Type: Type of house driver lives in 
- Casualty Class: Class of the person injured or killed in an accident (victim)
- Sex of Casualty: Sex of the person injured or killed in the accident (victim)
- Age Band of Casualty: Age range of person injured or killed in the accident (victim)
- Casualty Severity: severity of the injuries of the victim
- Pedestrian Location: Location of pedestrain
- Pedestrian Movement: Movement of pedestrain
- Car Passenger: Number of passengers in the car
- Bus or Coach Passenger: Number of passengers in bus or coach
- Pedestrian Road Maintenance Worker (From 2011): Presence of maintainance worker at pedestrain road
- Casualty Type: Type of person involved in the accident as the victim
- Casualty IMD Decile: Dimension of the deprivation scores of the victim
- Casualty Home Area Type: Type of house that the victim lives in


### Others
- Date (DD/MM/YYYY) : Date in which accident occured
- Day of Week --> cat: Day of the week in which accident occured
- Time (HH:MM): Time at which accident occured
- 1st Road Number: A number or an identifying numeric designation assigned by a highway authority to distinguish it from other roads
- 2nd Road Number: A number or an identifying numeric designation assigned by a highway authority to distinguish it from other roads
- Lower Super Ouput Area of Accident_Location (England & Wales only): Area of the accident site (England & Wales only)
- Vehicle Reference: Reference of vehicle
- Casualty Reference: Reference of the victim involved


## References:

(2013, October 21). Easting and northing. Retrieved from:
http://wiki.gis.com/wiki/index.php/Easting_and_northing#:~:text=The%20terms%20easting%20and%20northing%20are%20geographic%20Cartesian,commonly%20measured%20in%20meter%20s%20from%20a%20horizontal%20datum.

Kelly,I. (2018, October 29).Engine Capacity- what does cc mean? Retrieved from:
https://www.carsguide.com.au/car-advice/engine-capacity-what-does-cc-mean-70785#:~:text=Put%20simply%2C%20engine%20capacity%20is%20a%20measurement%20of,added%20together%20and%20displayed%20as%20a%20round%20figure.

NHS England. (n.d.). Indices of multiple deprivation (IMD) decile. Retrieved from:
https://data.england.nhs.uk/ncdr/data_element/indices-of-multiple-deprivation-imd-decile/

(2020, July 23). 10 Techniques to deal with Imbalanced Classes in Machine Learning. Retrieved from:
https://www.analyticsvidhya.com/blog/2020/07/10-techniques-to-deal-with-class-imbalance-in-machine-learning/

Li, S. (2019, February 27). Building a logistic regression in Python, step by step. Medium. Retrieved April 24, 2022, from https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8#:~:text=Logistic%20Regression%20is%20a%20Machine,%2C%20failure%2C%20etc.). 

Navlani, A. (2018, May 16). Sklearn Random Forest classifiers in python tutorial. DataCamp Community. Retrieved April 24, 2022, from https://www.datacamp.com/community/tutorials/random-forests-classifier-python 

Brownlee, J. (2021, January 4). Random oversampling and undersampling for imbalanced classification. Machine Learning Mastery. Retrieved April 24, 2022, from https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/ 


## Contributions:

Sahana: numerical data (EDA and ML, insights), slides, dataset and visualisation, data cleaning

Pareena: categorial data (EDA and ML, insights), slides, dataset and visualisation, data cleaning

Hillary: categorial data tree (ML, solutions), slides, dataset and visualisation, ReadMe file, video editing
