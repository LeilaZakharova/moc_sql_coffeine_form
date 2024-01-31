# DataCamp sample exam: coffee shops

## Task conditions:
Caffeine Form is a company creating coffee cups from recycled material.
Caffeine Form sells cups to coffee shops through their website. They would prefer to partner directly with the shops.
The company believes that stores with more reviews will help them to better market their product.
The company want to focus on the types of shop that get the most reviews.
They want you to investigate how types of shop and number of reviews are related.

### Task 1
Before you start your analysis, you will need to make sure the data is clean.
The table below shows what the data should look like.
Create a cleaned version of the dataframe.

Column names criteria:

1. "Region": 
Where the store is located. One of 10 possible regions (A to J).
Missing values should be replaced with “Unknown”.
2. "Place name": 
The name of the store. Missing values should be replaced with “Unknown”.
3. "Place type": 
The type of coffee shop. One of “Coffee shop”, “Cafe”, “Espresso bar”, and “Others”.
Missing values should be replaced with “Unknown”.
4. "Rating": 
Average rating of the store from reviews. On a 5 point scale.
Missing values should be replaced with 0.
5. "Reviews": 
The number of reviews given to the store.
Missing values should be replaced with the overall median number, rounded to the nearest interger value.
6. "Price": 
The price range of products in the store. One of '$', '$$' or '$$$'.
Missing values should be replaced with "Unknown".
7. "Delivery option": If delivery is available. Either True or False.
Missing values should be replaced with False.
8. "Dine in option": If dine in is available. Either True or False.
Missing values should be replaced with False.
9. "Takeout option": If take away is available. Either True or False.
Missing values should be replaced with False.

### Task 2

The team at Caffine Form believe that the number of reviews changes depending on the type of store.
Producing a table showing the difference in the median number of reviews by rating along with the minimum and maximum 
number of reviews to investigate this question for the team.