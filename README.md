# Flight_Fare_Prediction
## Problem Statement

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.
Size of training set: 10683 records

## About the Project

- The Flight Fare Prediction  project is to predict airline flight fares across the Indian cities. The dataset for the project is taken from Kaggle, and it is a time-stamped dataset so, while building the model, extensive pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The dataset had many features which had to pre-processed and transformed into new parameters for a cleaner and simple web application layout to predict the fares. The various independent features in the dataset were:

- Attribute Information
The various featureof the dataset explained below

- Airline: So this column will have all the types of airlines like Indigo, Jet Airways, Air India, and many more.
- Date_of_Journey: This column will let us know about the date on which the passenger’s journey will start.
- Source: This column holds the name of the place from where the passenger’s journey will start.
- Destination: This column holds the name of the place to where passengers wanted to travel.
- Route: Here we can know about what the route is through which passengers have opted to travel from his/her source to their destination.
- Arrival_Time: Arrival time is when the passenger will reach his/her destination.
- Duration: Duration is the whole period that a flight will take to complete its journey from source to destination.
- Total_Stops: This will let us know in how many places flights will stop there for the flight in the whole journey.
- Additional_Info: In this column, we will get information about food, kind of food, and other amenities.
- Price: Price of the flight for a complete journey including all the expenses before onboarding.
The code is written in Python 3.6.10. If you don't have Python installed, you can find it on google. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, check the project file in the project directory after cloning the repository.

## Cleaning the Data

I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:
- Calculated the total flight duration
- Removed the null values

## Business Goal
The goal is to build a regression model to predict the fare of flights based on various features and analysis.which will help the customers make informed decisionns and airline optimize pricing strategies.



