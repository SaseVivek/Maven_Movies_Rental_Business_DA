# Maven_Movies_Rental_Business_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business

## Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

## Project Objectives:

### Customer Insights:

Identify customer details (names, emails) for targeted marketing campaigns.
Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:

Explore the rental inventory and classify movies based on rental rates and availability.
Provide recommendations for expanding the movie collection based on popularity and rental rates.
Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories.
Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:

Help track and manage movie inventory effectively.
Highlight gaps in the inventory and optimize stock levels.


# Tools & Library Used
<img src="./IMAGES/mysql_img.png" alt="mysql_img.png" width="200"/> &nbsp;

# Project Result

[Click here to get full code](https://github.com/MaithiliGajbhiye/Maven_Movies_Rental_Business_DA/blob/main/MOVIES_RENTAL_CODE.sql)

# Query Task

1. How can we extract the first name, last name, and email address of all customers to prepare a comprehensive contact list for the marketing team?

<img src="./IMAGES/email.png" alt="email.png" width="400"/> &nbsp;


2. What is the total number of movies in the inventory that are available for rent at the lowest rental rate of $0.99?

<img src="./IMAGES/CHEAPEST_RENTAL.png" alt="CHEAPEST_RENTAL.png" width="200"/> &nbsp;


3. How can we categorize all movies based on their rental rates and determine the count of movies in each category?

<img src="./IMAGES/TOTAL_NO_OF_MOVIES.png" alt="TOTAL_NO_OF_MOVIES.png" width="400"/> &nbsp;


4. Which movie rating (e.g., PG, PG-13, R) has the highest number of titles in the inventory, and how can this information help optimize inventory management?

<img src="./IMAGES/rating_wise_count.png" alt="rating_wise_count.png" width="400"/> &nbsp;


5. What is the total count of PG-rated movies that have been rented, and what does this indicate about customer preferences?

<img src="./IMAGES/TOTAL_FILMS.png" alt="TOTAL_FILMS.png" width="400"/> &nbsp;

6. List of films by Film Name, Category, Language.

<img src="./IMAGES/TLC.png" alt="TLC.png" width="400"/> &nbsp;

7.How many times each movie has been rented out?

<img src="./IMAGES/popularity.png" alt="popularity.png" width="400"/> &nbsp;

8.Revenue per film (Top 10 Grossers)

<img src="./IMAGES/REVENUE.png" alt="REVENUE.png" width="400"/> &nbsp;

9.Which store has historically brought the most revenue?

<img src="./IMAGES/MOST_REVENUE.png" alt="MOST_REVENUE.png" width="400"/> &nbsp;

10.How many rentals we have each month?

<img src="./IMAGES/RENTALS_PER_MONTH.png" alt="RENTALS_PER_MONTH.png" width="400"/> &nbsp;

11.Reward users who have rented at least 30 times (With details of customers).

<img src="./IMAGES/REWARD_VIA_PHONE.png" alt="REWARD_VIA_PHONE.png" width="400"/> &nbsp;

12.Could you pull all payments from our first 100 customers (Based on customers id)

<img src="./IMAGES/FIRST_100_CUSTOMER_PAYMENTS.png" alt="FIRST_100_CUSTOMER_PAYMENTS.png" width="400"/> &nbsp;

13.Now I’d love to see just payments over $5 for those same customers, since January 1, 2006

<img src="./IMAGES/JAN_06_2006.png" alt="JAN_06_2006.png" width="400"/> &nbsp;

14.Now, could you please write a query to pull all payments from those specific customers, along with payments over $5, from any customer?

<img src="./IMAGES/PAYMENTS_OVER_$5.png" alt="PAYMENTS_OVER_$5.png" width="400"/> &nbsp;

15.We need to understand the special features in our films. Could you pull a list of films which include a Behind the Scenes special feature?

<img src="./IMAGES/BTS.png" alt="BTS.png" width="400"/> &nbsp;

16.Most Spending Customer so that we can send him/her rewards or debate points.

<img src="./IMAGES/MOST_SPENDING_CUSTOMER.png" alt="MOST_SPENDING_CUSTOMER.png" width="400"/> &nbsp;

17.Could you please pull a count of titles sliced by rental duration?

<img src="./IMAGES/SLICED_BY_RENTAL_RATE.png" alt="SLICED_BY_RENTAL_RATE.png" width="400"/> &nbsp;

18.RATING, COUNT_MOVIES,LENGTH OF MOVIES AND COMPARE WITH RENTAL DURATION

<img src="./IMAGES/COMPARE_WITH_RENTAL_DURATION.png" alt="COMPARE_WITH_RENTAL_DURATION.png" width="400"/> &nbsp;

19. I’m wondering if we charge more for a rental when the replacement cost is higher. Can you help me pull a count of films, along with the average, min, and max rental rate, grouped by replacement cost?

<img src="./IMAGES/MIN_MAX_AVG.png" alt="MIN_MAX_AVG.png" width="400"/> &nbsp;

20. CATEGORIZING MOVIES TO RECOMMEND VARIOUS AGE GROUPS AND DEMOGRAPHIC.

<img src="./IMAGES/FIT_FOR_RECOMMENDATION.png" alt="FIT_FOR_RECOMMENDATION.png" width="400"/> &nbsp;

21. “I’d like to know which store each customer goes to, and whether or not they are active. Could you pull a list of first and last names of all customers, and label them as either ‘store 1 active’, ‘store 1 inactive’, ‘store 2 active’, or ‘store 2 inactive’?”

<img src="./IMAGES/ACTIVE_STORE.png" alt="ACTIVE_STORE.png" width="400"/> &nbsp;

22. “Can you pull for me a list of each film we have in inventory? I would like to see the film’s title, description, and the store_id value associated with each item, and its inventory_id. Thanks!”

<img src="./IMAGES/FILMS_IN_INVENTORY.png" alt="FILMS_IN_INVENTORY.png" width="400"/> &nbsp;   
