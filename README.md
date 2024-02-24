<h1>Predicting Airline Passenger Satisfation with help of ML</h1>

<p>With the help of various python based machine learning and data science tools we're going to analyse and train the data. Then we'll make an attempt to build a machine learning model based on our information. The ML model will help us to predict whether a passenger is satisfied with the airline service or not.</p>

## Steps we're going to follow-

1. Defining Problem
2. Data Description
3. Importing Data
4. Data Exploration
5. Data Summarisation
6. Modelling
7. Experimentation & Evaluation
8. Conclusion & References

# Defining Problem

Given the airline passenger satisfaction survey information about the passengers, can we predict whether they are satisfies or not with the airline services ? Also what factors are highly correlated to a satisfied (or dissatisfied) passenger?

# Data Description

The given data is taken from Maven Analytics. The dataset contains 24 different attributes and 129880 records.

Gender: Gender of the passengers
Male : Male Passenger
Female : Female Passenger

Customer Type: The customer type as per loyality and behaviour
Loyal Customer
Disloyal Customer

Age: The actual age of the passengers
In Range

Type of Travel: Purpose of the flight of the passengers
Personal Travel
Business Travel

Class: Travel class in the plane of the passengers
Eco : Economy Class
Eco Plus : Premium Economy Class
Business : Business Class

Flight distance: The flight distance of this journey
Inflight wifi service: Satisfaction level of the inflight wifi service
0 : Not Applicable
General Rating: 1-5

Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
0 : Not Applicable
General Rating: 1-5

Ease of Online booking: Satisfaction level of online booking
0 : Not Applicable
General Rating: 1-5

Gate location: Satisfaction level of Gate location
0 : Not Applicable
General Rating: 1-5

Food and drink: Satisfaction level of Food and drink
0 : Not Applicable
General Rating: 1-5

Online boarding: Satisfaction level of online boarding
0 : Not Applicable
General Rating: 1-5

Seat comfort: Satisfaction level of Seat comfort
0 : Not Applicable
General Rating: 1-5

Inflight entertainment: Satisfaction level of inflight entertainment
0 : Not Applicable
General Rating: 1-5

On-board service: Satisfaction level of On-board service
0 : Not Applicable
General Rating: 1-5

Leg room service: Satisfaction level of Leg room service
0 : Not Applicable
General Rating: 1-5

Baggage handling: Satisfaction level of baggage handling
0 : Not Applicable
General Rating: 1-5
Check-in service: Satisfaction level of Check-in service
0 : Not Applicable
General Rating: 1-5

Inflight service: Satisfaction level of inflight service
Cleanliness: Satisfaction level of Cleanliness
0 : Not Applicable
General Rating: 1-5

Departure Delay in Minutes: Minutes delayed when departure
In Continous Range (Minutes)

Arrival Delay in Minutes: Minutes delayed when Arrival
In Continous Range (Minutes)

Satisfaction: Airline satisfaction level ( Prediction Target )

Satisfaction (1) : Overall satisfied with the services
Neutral or Dissatisfaction (0) : Overall unsatisfied with the services

# Importing data and important libraries
Modules we are going to use : Pandas, Numpy, Plotly, Matplotlib, Seaborn, Jovian, Joblib, XGBoost, Scikit-Learn.
In this section we are going to import our basic required files and modules which need for Exploratory Data Analysis and further Data Pre-processing.

# Model Building 
We used various ML algorithms to build model and to make prediction. Out of that Gradient Boosting gives better results as compared to others.

# Evalution metrics
We achieve following results of different metrics :
1. Accuracy = 95%
2. Precision = 95%
3. Recall = 96%
4. f1 score = 94%


# Author :
          Rupesh More


