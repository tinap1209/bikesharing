# NYC CitiBike Challenge

## Background

Citi Bike, NYC's official bike share program, was designed to give residents and visitors a fun, affordable and convenient alternative to walking, taxis, buses and subways.

There are 800 Citi Bike stations and 13,000 bikes across Manhattan, Brooklyn, Queens and Jersey City.

You can join as an Annual Member (Subscriber) or buy a Day Pass or 3-Day Pass (Customer), and you can take as many rides as you want while your membership or pass is active.

## Project 

To implement a dashboard or reporting process for answering City officials questions on the program taking in consideration the bike data collected, organized, and made public on the Citi Bike System Data, using Tableau.

## Data Source
CSV files from [citybank Data](https://www.citibikenyc.com/system-data) and (https://s3.amazonaws.com/tripdata/index.html) for the month of August.

## Challange Deliverables 
-Deliverable 1: Change Trip Duration to a Datetime Format
-Deliverable 2: Create Visualizations for the Trip Analysis
-Deliverable 3: Create a Story and Report for the Final Presentation

## My Visualizations
https://public.tableau.com/profile/ms.tina.singh#!/vizhome/NYC_CitiBank_Challenge_presentationforApril2021/PresentationforBusinessProposal

## Analysis
### 1. Checkout Times for Users:
Over 1,00,000 users bike for 10 mins. But what looks like the average duration, is 60 mins.
<img width="688" alt="Users" src="https://user-images.githubusercontent.com/76264061/113516492-2d268980-9598-11eb-9aea-5cf16c241b4a.png">

### 2. Checkout Times by Gender
The below graph clearly shows that there are more male bikers than female bikes. There is a difference of nearly 50% more male bikers then female bikes. 

<img width="681" alt="gender" src="https://user-images.githubusercontent.com/76264061/113516622-e4230500-9598-11eb-88ae-977985eb4e81.png">

### 3. Trips by Weekday for Each Hour
It clearly looks like the most preferred time slot to bike is in between 6 am to 10 am and 5 pm to 7 pm.
<img width="679" alt="time" src="https://user-images.githubusercontent.com/76264061/113516696-5267c780-9599-11eb-8c00-c6d2103296b9.png">

### 4. Trips by Gender (Weekday per Hour) 
The most number of bikers in the weekday are males in between 6 am to 9 am and evenings in between 4pm to 8pm.
<img width="679" alt="time" src="https://user-images.githubusercontent.com/76264061/113516696-5267c780-9599-11eb-8c00-c6d2103296b9.png">

### 5. Trips by Gender by Weekday
Female subcribers make lesser trips than male subsribers. 
<img width="800" alt="subcribers" src="https://user-images.githubusercontent.com/76264061/113517038-4977f580-959b-11eb-91ce-ee9ff77644d2.png">

# Two additional visualizations of NYC Citibike analysis for future references. 

## 1. Symbol Map for future reference. 
<img width="681" alt="Module 1" src="https://user-images.githubusercontent.com/76264061/113517605-9dd0a480-959e-11eb-9a4c-c7a159200abe.png">

## 2. Average Trip Duration by Age.
<img width="679" alt="Module 2" src="https://user-images.githubusercontent.com/76264061/113517741-85ad5500-959f-11eb-80cd-84c293653979.png">

## Deliverables 
The jupyter notebook is uploaded on Github for reference.

## Summary 
In this dashboard there are additional filters for the user to explore, gender and usertype. Understanding the trips by usertype and gender, clearly shows that subscribers make up a large number of the trips, however customers tend to make longer trips. This makes sense because subscribers are every day commuters who probably commute to work only during the weekdays, whereas customers are most likely travelers who like to explore the city. However, it must be noted that within subscribers the gap between the number of trips made by each gender is large. Female subscribers make less trips than male subscribers. Therefore something must be done to attract more female riders. Looking over to the time breakdown, there is no difference between the usertype or genders. The preferred time is between 4pm and 7pm. It may be possible to move the less popular stations to higher female population areas as well.

