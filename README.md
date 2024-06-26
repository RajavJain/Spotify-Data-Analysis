# Music Store Data Analysis 🎧

## Objective

This project aims to perform data analysis on a digital music store using SQL. The dataset includes information such as customer details, genre, and music tracks. The goal is to extract meaningful insights from the data and provide recommendations to improve the store’s performance.

## Database and Tools

- PostgreSQL
- PgAdmin4

## Schema - Music Store Database

![screenshot](schema_diagram.png)

## Query Categorization

In this project, I have categorized the queries I worked on into different difficulty levels:

### Easy

- **Retrieve the employee with the highest level.**
- **Get the count of invoices for each billing country, ordered by the count.**
- **Fetch the top 3 invoices with the highest total.**
- **Calculate the total invoice amount for each billing city, ordered by the invoice total.**
- **Find the customer who has spent the most money in total, including their name and customer ID.**

### Moderate

- **Retrieve the email, first name, and last name of customers who have purchased rock genre tracks.**
- **Find the top 10 artists with the most songs in the rock genre, including their artist ID and name.**
- **Retrieve the names and durations of tracks that have a duration longer than the average track length.**

### Advanced

- **Determine the best-selling artist based on total sales generated from their tracks.**
- **Identify the most popular genre in each country, including the genre name, country, and the number of purchases, using row number ranking.**
- **Retrieve customer details (ID, first name, last name), along with the best-selling artist they have purchased from and the total amount spent by the customer.**

These queries provide insights into various aspects of the music store data and demonstrate different levels of complexity in data analysis.

## Results

The results of the project are as follows:

- The most popular genre of music is **"Rock"**.
- The most popular artist is **"Queens"**.
- The most popular song is **"War Pigs"**.
- The average price of an album is **$1**.
- The most popular country for music purchases is the **United States**.

Some of the analysis is mentioned above, and the rest can be seen through the [Spotify_queries.sql](Spotify_queries.sql) file.

## Conclusion

The project was successful in answering the set of questions about the store's business performance. The results of the project can be used by the store to make decisions about its marketing and product offerings.
