#Air Quality Prediction App

This application is made for predicting Air Quality i.e PM 2.5.

I used techniques of web scraping to find the dataset.

There are 8 Idependent features and 1 Independent feature.
The Independent Features:
T - Temperature
TM - Maximum Temperature
Tm - Minimum Temperature 
SLP - Atmospheric pressure
H - Humidity
VV - Average Visibility
V - Wind Speed
VM - Maximum Wind Speed

There is 1 Independent feature:
PM 2.5 - PM2.5 refers to atmospheric particulate matter (PM) that have a diameter of less than 2.5 micrometers, which is about 3% the diameter of a human hair. 

I used a basic algorithm called Linear regression in my model.

I used Flask and then Heroku for deployement of my project. 

![image](https://user-images.githubusercontent.com/42106966/116661678-79f05b00-a9b2-11eb-99f7-9476fdeb680d.png)



![image](https://user-images.githubusercontent.com/42106966/116661789-9be9dd80-a9b2-11eb-8eac-76a859712566.png)
In the above figure, after clicking the predict button, I have the passed the data of 2018, and the predicted their correspondng AQI's.
