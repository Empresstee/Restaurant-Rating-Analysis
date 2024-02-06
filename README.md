## Restaurant-Rating-Analysis

### Project Overview 

Dataset Understanding: This Project has five (5) different files in CSV format — restaurants, restaurant_cuisines, consumer_preferences, consumers, and ratings. The restaurant's table has 131 rows and 14 columns including Restaurant_ID, Name, city, State, Country, etc. The Restaurants_cuisines table has 113 rows and two (2) Columns as Restaurant_ID and cuisine. While customer_preferences contains 331 rows and two columns as customer_ID and preferred_cuisine the consumers table also has 14 columns and 139 rows. The ratings table, however, has 1162 rows and five Columns consumer_ID, Restaurant_ID, Overall_rating, food_rating, and Service_rating.


### Data Transformation and Cleaning:
the first thing I did was to load the different Datasets into the Power Query editor and did some Appending and Merging to enable access to one Dataset for easy.

### Report and Visualization KPIs:
- Total No. of Restaurant = COUNTROWS(Restaurant_Rating) 
 
- TotalNo.ofConsumers= DISTINCTCOUNT(Restaurant_Rating[Consumer_ID_2]) 

- Total Overall Rating = SUM(Restaurant_Rating[Overall_Rating]) 
 
- Total Food Rating = SUM(Restaurant_Rating[Food_Rating]) 
 
 - Total Service Rating = SUM(Restaurant_Rating[Service_Rating])
