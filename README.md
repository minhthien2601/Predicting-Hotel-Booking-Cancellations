# Predicting-Hotel-Booking-Cancellations
## Introduction
The rate of cancellation for bookings in the hospitality industry is quite high in the competitive market offering no deposit bookings. Once the booking has been cancelled, there is almost nothing to be done at the end of hotel. This kind of setting creates discomfort and monetary losses for many hotels and creates a demand to take prior precautions for high number of cancellations. Therefore, predicting bookings that can be cancelled and preventing these cancellations will create value for hospitality industry. With the help of this project, we will try to explain how future cancelled hotel bookings can be predicted in advance with the help of machine learning methods. Also, what measures and steps can be implemented for reducing their impact on industry’s revenue.

## Problem Statement:
### Research Problem Statement
In this proposed project, we will be predicting whether a booking made in a hotel can be cancelled in future or not. For this, we have developed models that will identify and flag bookings with high cancellation probability by understanding the trends and features associated with it. Thus, hotels can act on these booking to contain the associated revenue losses. This kind of prediction will help in producing better net demand forecasts, improve overbooking/cancellation policies, and have more assertive pricing and inventory allocation strategies. This analysis can also be used by hotels to identify their loyal customers who never cancel their booking and can provide loyalty benefits.

### Questions:

1. How do customer groups affect the cancellation rate?
2. If the customer booked room A and checked into room B, will the room be canceled?
3. Will returning old customers cancel the room?
4. What type of hotel do customers cancel?
5. Couples, friends, families or singles will be the group that cancels the most?
6. Where do guests come from most often?
7. Usually, customers who order through, will cancel a lot?
8. If customers book early or close to the date, how will it affect the cancellation rate?
9. The faster the hotel closes the booking, will the customer cancel the room?
10. What type of meal will get canceled the most
11. Guests requesting for parking, will they cancel the room or not?
12. Customers with special requirements, how do they affect the cancellation?

## Limitation
• This hotel cancellation project only applies to hotel bookings in Lisbon Region and Algarve Region, both locations in Portugal.\
• Predictions of cancellations with this web app outside of both regions may not be available accurate results due to location restrictions, cancellation differences

## Machine Learning: Solving a Classification Problem
By means of Machine Learning it was to determine if a prediction can be made with a high probability whether guests set forth on a journey or whether they cancel the planned hotel overnight stays.

Contrary to other data scientists working on this dataset I did not try to reach > 99% accuracy due to the danger of overfitting.

## The Classification Methods I Used:
Logistic Regression/
Decision Tree/
KNN/
Random Forest/
Ada Boost Classifier/
XgBoost Classifier

## Data Acquisition
For this project, we are using Hotel Booking Demand from Kaggle. This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

## Dataset
<a href="https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand">Mostipak, J. (2020, February 13). Hotel booking demand</a>

The dataset comes from 2 Portugese hotels, a city and a resort hotel. It contains overnighters from the years 2015, 2016, and 2017 as well as cancelled bookings.

## Libraries Used
### Python
Python Standard Library: Built in python modules.
Numpy: Scientific computing with python.\
Pandas: Data analysis tools.\
matplotlib: Static, animated, and interactive visualizations.\
Seaborn: Python data visualization library.
