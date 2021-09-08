
This blog purpose is analysing Airbnb bookings in Seattle to understand more how bookings are done, I will use CRISP-DM to answer the following questions in this blog:

1. The most booked Seattle neighborhoods using listing descriptions
2. What factors affect the above behavior?
3. What factors affect the price of the neighborhood booking?
4. What might influence reviewer rating?
5. What are the busiest times of the year to visit Seattle? and its reflection on prices?

DATA
In this project I used 2 datasets from Kaggle Seattle Airbnb Page https://www.kaggle.com/airbnb/seattle/data:

Data Understanding
First, let us have a look at the listings dataset to understand more about bookings in seattle through Airbnb

Overview of listings dataset
Read the csv file using pandas as given below:

Observations about the dataset:

1. There are 3813 records in this dataset with around 92 attributes
2. There are 4 attributes with missing data more than 50 % of the records of the attribute

After data preparation and cleansing, now let's try to answer the above questions

Q1: What are the most booked Seattle neighborhoods?

Using the attribute of the "neighbourhood_group_cleansed" which groups the neighborhoods and by excluding the "other Neighborhoods" we can see that "Capitol Hill" , "Down Towm" and "Central Area" are the top 3 booked neighborhoods in the dataset

Q2: What factors affect the above behavior?

If we explore the dataset more, we can see that the above top neighborhoods provide the highest option in term of Entire home/apt property. Added to that Central Area has advantage with the highest hospitality ratio

Q3: What factors affect the price of the neighborhood booking?

If we check the above list, we can see that "Magnolia", "Queen Ann" and "Down Town" are the top 3 expensive neighborhoods. If we explore the data deeper we will find that these 3 neighborhoods are among the most spacious properties in terms of property type, number of rooms, number of bedrooms and even the number of guests it can hold

Q4: What might influence review rating for a booking?

Analysing the reviewers ratings, we can see that "Central Area", "Delridge" and "West Seattle" are the highest rated neighborhoods. If we search for the reason, we can find that for example "Central Area" and "Delridge" are among the highest super hospitality index, while for example "Central Area" and "West Seattle" are among the most spacious properties which explains why "Central Area" is the highest rated neighborhood

Q5:What are the busiest times of the year to visit Seattle? and its reflection on prices?

Based on the above chart, we can see that July,August and June are the busiset month among the year in seattle and as a result we can see these 3 months are the most expensive along the year
