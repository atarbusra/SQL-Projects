# An SQL Project for Green Cycles Movie Rental Shop
This SQL project includes data analysis queries of an online movie rental shop called Green Cycles.
## Overview
This repository contains SQL projects that analyze various aspects of customer behavior, movie details, and revenue for an online movie rental shop called Green Cycles. The queries cover a range of SQL concepts including JOINs, subqueries, CASE statements, and more.

## Project Contents
### 1. Average Customer Lifetime Value with Subqueries
This query calculates the average customer lifetime value using subqueries to aggregate rental and payment data.

### 2. Film Categories with JOIN & GROUP BY
This query demonstrates how to use JOIN and GROUP BY to categorize movies based on their genres and calculate related statistics.

### 3. Length of Movies with Replacement Costs using Correlated Subquery
This query finds the lengths of movies alongside their replacement costs using a correlated subquery to get precise cost details for each movie.

### 4. Longest Movie with INNER JOIN
A simple query to retrieve the longest movie available in the database, using an INNER JOIN to combine related tables.

### 5. Replacement Cost Ranges with CASE-WHEN
This query categorizes movies into different ranges of replacement costs using the CASE-WHEN statement.

### 6. Revenue per Customer and Staff with Uncorrelated Subquery
Analyzes the revenue generated per customer and staff by using uncorrelated subqueries to fetch total revenue data.

### 7. Unknown Addresses with LEFT JOIN, Filtering, and CASE-WHEN-SUM
This query identifies records with missing address information using a combination of LEFT JOIN, filtering, and aggregating results with CASE-WHEN and SUM.

## Database
The data used for these queries is based on the Pagila sample database, a PostgreSQL sample schema designed for a DVD rental store.
