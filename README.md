# Music Store Data Analysis using SQL

### Project Overview
This project involves designing a database for a digital Music Store and running a series of analytical SQL queries to extract meaningful business insights. The dataset represents a fictional music store with information about customers, employees, tracks, invoices, genres, and more.

The goal of the project is to answer real-world business questions using SQL, helping stakeholders make informed decisions such as identifying top customers, understanding buying behavior, and planning promotions.

#### Technologies Used
SQL (MySQL syntax)

Database: Structured relational database using tables and foreign key relationships

#### Database Schema
The following tables were created and used:

albums

artist

customer

employee

genre

invoice

invoice_line

media_type

playlist

playlist_track

track

Each table stores a specific entity, and they are related via foreign keys to allow normalized and efficient queries.

Analytical Tasks & Insights
**Task Description**	                                                    **Insight/Output**
1	Who is the senior-most employee based on job title?	                     Employee with the highest job level
2	Which countries have the most invoices?	                                 Top countries by number of sales
3	Top 3 invoice totals?	                                                   Highest individual invoice amounts
4	Which city has the best customers (by total invoice amount)?	           City generating highest revenue
5	Who is the best customer (most money spent)?	                           Customer with the highest spending
6	List all Rock music listeners ordered by email alphabetically.	         Rock genre listeners with email
7	Top 10 artists who have written the most rock music.	                   Artists with highest track counts in Rock
8	Tracks longer than average song length.	                                 Tracks with length above average
9	Total amount spent by each customer on each artist.	                     Customer-Artist-wise spending
10	Most popular music genre per country.	                                 Top genre per country by purchase
11	Top spending customer per country.	                                   Best customer by country

### Key Learnings
Writing complex queries using JOIN, GROUP BY, ORDER BY, and subqueries.

Using window functions like RANK() for partitioned ranking tasks.

Understanding how to normalize data and utilize relational databases for real-world scenarios.

Applying analytical thinking to answer business questions using SQL.

music-store-sql-analysis
├── 📄 schema.sql            # All table creation scripts
├── 📄 queries.sql           # All analytical queries
└── 📄 README.md             # Project documentation (this file)

### Conclusion
This project demonstrates the power of SQL in uncovering valuable business insights from structured data. By designing and querying a comprehensive music store database, we explored real-world use cases such as identifying top customers, analyzing genre popularity across countries, and understanding revenue distribution.

From simple aggregations to advanced window functions and subqueries, this project showcases how SQL can answer critical questions that drive data-informed decisions. Whether it's planning a promotional event or understanding customer preferences, these insights can help businesses in the music industry optimize strategies and improve customer experience.

Overall, this project not only strengthens SQL skills but also highlights how data analysis can directly impact business outcomes in a digital-first world.
