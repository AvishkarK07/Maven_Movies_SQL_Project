# Maven_Movies_SQL_Project
![Project Banner](https://github.com/AvishkarK07/Maven_Movies_SQL_Project/blob/main/Code_Output/New-Cinema-Age-Classifications-in-the-UAE-Cover-01-12-23-2021.jpg)

# Maven Movies SQL Analysis

This project contains **SQL queries** performed on the **Maven Movies** database for exploratory data analysis (EDA).  
It is designed to practice SQL concepts such as filtering, grouping, aggregation, and joins.

---

## 📂 Project Structure
- `8f179d7e-bdff-4815-826d-69554d2d0520.sql` → SQL file containing exploratory queries.

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
