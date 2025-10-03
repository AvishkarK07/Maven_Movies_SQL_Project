# 🎬 Maven Movies Analysis 

![Project Banner](https://github.com/AvishkarK07/Maven_Movies_SQL_Project/blob/main/Code_Output/New-Cinema-Age-Classifications-in-the-UAE-Cover-01-12-23-2021.jpg)

This project contains **SQL queries** performed on the **Maven Movies** database for exploratory data analysis (EDA).  
It is designed to practice SQL concepts such as filtering, grouping, aggregation, and joins.

---

## 🎯 Project Goals

### 🛒 Customer Insights

- 📌 Identify customer details (names, emails) to enhance targeted marketing campaigns.
- 📊 Analyze rental behavior to improve customer engagement.

### 🎮 Movie Inventory Optimization

- 🛆 Evaluate rental inventory and categorize movies based on rental rates and availability.
- 🔍 Suggest recommendations for expanding the movie collection based on popularity and rental trends.

### 💰 Revenue Enhancement

- 📈 Examine rental pricing trends to identify profitable pricing strategies.
- 🎥 Determine the most rented movie categories and ratings to maximize earnings.

### ⚙️ Operational Efficiency

- 📌 Track and manage movie inventory efficiently.
- 📉 Identify inventory gaps and optimize stock levels.

---

## 🛠️ Tools & Technologies Used
- SQL – Data extraction, transformation, and querying
- MAVENMOVIES Database – Source of movie rental data
---

## 🗄 Database Overview
The database `MAVENMOVIES` includes several tables, such as:
- **RENTAL** → Contains rental transactions.
- **CUSTOMER** → Stores customer details.
- **FILM** → Stores movie-related details (title, rating, rental rate, etc.).
- **INVENTORY** → Maps films to stores.

---

## 🔍 Queries Included
Some key analyses performed in this project:
- List of all rentals and customers.
- Customer first name, last name, and email for marketing purposes.
- Count of movies with rental rate = **$0.99**.
- Distribution of movies by `rental_rate`.
- Most common **film ratings**.
- Most common **rating per store**.

---

## 🚀 How to Use
1. Open MySQL Workbench (or any SQL client).
2. Create and select the database:
   ```sql
   USE MAVENMOVIES;

## Movies Rental Data Queries

This repository contains SQL queries and corresponding visualizations for analyzing the Movies Rental dataset.

## Queries and Visualizations

### 1. Customer Information for Marketing Team
Customer Firstname, Lastname and Email Id to The Marketing Team.

![Customer Info](https://github.com/AvishkarK07/Maven_Movies_SQL_Project/blob/main/Code_Output/Q1.png)

### 2. Count of Movies with Rental Rate of $0.99
![Cheapest Rental](https://github.com/AvishkarK07/Maven_Movies_SQL_Project/blob/main/Code_Output/Q2.png)

### 3. Rental Rate Distribution and Movie Count
![Total Movies per Rental Rate](https://github.com/AvishkarK07/Maven_Movies_SQL_Project/blob/main/Code_Output/Q3.png)

### 4. Most Common Movie Rating
![Rating Count](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/rating_wise_count.png)

### 5. Most Prevalent Rating per Store
![Rating per Store](https://github.com/Athu087/Movies_rental/blob/d5bf4597456956ee94bc974f6f54cd4122f0b2ff/images/rating_to_store.png)

### 6. List of Films by Name, Category, and Language
![Film List](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/TLC.png)

### 7. Movie Rental Frequency
![Rental Popularity](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/popularity.png)

### 8. Top 10 Grossing Films
![Revenue per Film](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/REVENUE.png)

### 9. Highest Spending Customer
![Most Spending Customer](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/MOST_SPENDING_CUSTOMER.png)

### 10. Store with Most Revenue
![Highest Revenue Store](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/MOST_REVENUE.png)

### 11. Monthly Rentals Count
![Rentals Per Month](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/RENTALS_PER_MONTH.png)

### 12. Customers Eligible for Rewards
![Reward Eligible Customers](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/REWARD_VIA_PHONE.png)

### 13. Payments from First 100 Customers
![First 100 Customer Payments](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/FIRST_100_CUSTOMER_PAYMENTS.png)

### 14. Payments Over $5 Since Jan 1, 2006
![Payments Over $5](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/JAN_06_2006.png)

### 15. Payments Over $5 for Specific Customers
![Payments Over $5](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/PAYMENTS_OVER_%245.png)

### 16. Films with 'Behind the Scenes' Special Feature
![Behind the Scenes Films](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/BTS.png)

### 17. Unique Movie Ratings and Count
![Unique Ratings](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/UNI_MOVIES_RATINGS_%26_NO_OF_MOVIES.png)

### 18. Titles Count by Rental Duration
![Rental Duration Count](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/SLICED_BY_RENTAL_RATE.png)



### 19. Film Count by Replacement Cost with Rental Rates
![Replacement Cost Analysis](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/MIN_MAX_AVG.png)



### 20. Longest Films Sorted by Length and Rental Rate
![Longest Films](https://github.com/Athu087/Movies_rental/blob/d5bf4597456956ee94bc974f6f54cd4122f0b2ff/images/longestfilms_sort.png)



### 21. Movie Recommendations by Age Group
![Age-Based Recommendations](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/FIT_FOR_RECOMMENDATION.png)

### 22. Films Inventory List
![Films in Inventory](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/FILMS_IN_INVENTORY.png)

### 23. Actor Movie Count
![Actor Movie Count](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/NO_OF_FILMS_BY_ACTOR.png)

### 24. Number of Actors per Film
![Actors per Title](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/ACTOR_ASSOCIATED_WITH_TITLE.png)

### 25. List of Staff and Advisors
![Staff and Advisors](https://github.com/Athu087/Movies_rental/blob/1dfa0affc2a0cd10a1b955543baf23680ec0fcac/images/UNION.png)

---
