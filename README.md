# Flight_fare_prediction
Introduction
The goal of this project is to predict flight fares using machine learning techniques. This can help users get an estimate of the fare before purchasing tickets, potentially saving them money by booking at the right time.

Dataset
The dataset used for this project contains flight information from various airlines with multiple features that influence the fare. The key input features are:

Airline: Name of the airline.
Date_of_Journey: The date on which the journey starts.
Source: The starting point of the journey.
Destination: The destination point of the journey.
Route: The route taken by the flight.
Dep_Time: The departure time of the flight.
Arrival_Time: The arrival time of the flight.
Duration: The total duration of the flight.
Total_Stops: The number of stops the flight makes before reaching the destination.
Additional_Info: Any additional information about the flight.
The output feature is the Flight Fare, which is the target variable.

Features
Input Features:
Airline: Categorical variable representing the airline company.
Date_of_Journey: Date when the flight is scheduled (in DD/MM/YYYY format).
Source: The departure city.
Destination: The destination city.
Route: The route the flight takes, showing layovers.
Dep_Time: Departure time (in HH
format).
Arrival_Time: Arrival time (in HH
format).
Duration: Total flight duration (in hours and minutes).
Total_Stops: Number of stops in the journey.
Additional_Info: Any extra information about the flight (e.g., "No Info", "In-flight meal not included", etc.).
Output:
Flight Fare: The predicted fare for the flight in a given currency (e.g., INR).

Model Training
The dataset was preprocessed by handling missing values, converting categorical variables using one-hot encoding, and normalizing numerical data. 
Training Steps:
Preprocess the dataset.
Split the data into training and testing sets.
Train multiple machine learning models and evaluate their performance.

Results
The model performs well , providing reliable fare predictions for most flights. Further improvements can be made with more data and tuning.
