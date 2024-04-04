# music-store-analysis-SQL

Overview:
This project involves analyzing a music store dataset using SQL queries to derive insights such as top customers, popular genres, sales trends, and more.

Dataset:
The dataset includes tables like customer, invoice, invoice_line, track, album, artist, genre, and employee.
CSV output files for query results are included in the repository.

SQL Queries:
Set 1 - Basic Analysis
Senior Most Employee: Identifies the most senior employee based on job title.
Top Invoiced Countries: Lists countries with the most invoices.
Top Invoice Values: Retrieves the top 3 invoice values.
Best Customer City: Determines the city with the highest sum of invoice totals.
Best Customer: Identifies the customer who has spent the most money.

Set 2 - Genre and Artist Analysis
Rock Music Listeners: Retrieves details of customers who listen to Rock music.
Top Rock Bands: Lists the top 10 rock bands based on the number of tracks.
Longest Tracks: Lists tracks longer than the average song length.

Set 3 - Advanced Analysis
Customer Spending on Artists: Determines the amount spent by each customer on artists.
Popular Genre by Country: Identifies the most popular music genre for each country.
Top Spender by Country: Identifies the top customer by spending for each country.

Files:
music_store_query.sql: Contains all SQL queries used in the analysis.
customer.csv, invoice.csv, ...: CSV files containing data used in queries.

Usage:
Execute the SQL queries in a PostgreSQL environment.
Analyze query results and derived insights.
Use CSV output files for further analysis or reporting.
