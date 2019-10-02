# Machine-Learning-NYC_Taxi

So far, we stayed in the first steps of this project which are Business understanding, Data Understanding & Data Preparation. To do so, we made some analysis on the data and run few statistical test. 

Concerning the Business Understanding, we figured out for each stakeholder of the project (Drivers, Customers, etc…) which variable we were going to use. This reduce the panda data frame by few and make the system easier. 

## Driver

Concerning the driver, with the data we selected, we could predict where the driver has to be at what time to increase his chances to get a client. Also, we could predict the number of client the driver should take if he wants to increase his tip/revenues. 

We are selecting the following fields: Trip Time, Fare Amount, Tip Amount, Total Amount, Passenger count Pickup Time, and Pickup coordinates (Pickup Latitude, Pickup Longitude) 
If we have time, we can add Pick

## Customers

As an international student living in the US, I am not used at all to give tip to the taxi driver. We don’t do this in Europe so here, I have no clue of how much should I give to the driver. We could create an algorithm based on the time, the localization, the time trip, if you have luggage or no, to predict how much to give to the driver. 

For this we would need this following fields: Trip Time (long? Short?), Pickup Time (night ? day ?), Passenger Count (1? 4?), Surcharge, Tip Amount, and Payment Fare. 
