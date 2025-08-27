# SQL Examination – Airbnb Open Data
## Overview

This project contains an SQL examination designed for students to assess their understanding of both theoretical SQL concepts and practical data analysis skills. The exam uses Airbnb Open Data, allowing students to work with a real-world dataset while demonstrating proficiency in writing SQL queries.

## Exam Structure
*Section A – Theory (20%)*
Covers fundamental SQL concepts:
- Data types and constraints
- Normalization and schema design
- Indexing and query optimization
- Primary vs foreign keys
- Transactions and ACID properties

*Section B – Practical (80%)*
Students analyze Airbnb data using SQL queries.
Topics include:
- Filtering and sorting (WHERE, ORDER BY)
- Aggregation and grouping (GROUP BY, HAVING)
- Joins between tables (INNER, LEFT, RIGHT)
- Subqueries and common table expressions (CTEs)
- Creating and modifying tables

## Dataset:
- The practical component uses Airbnb Open Data (publicly available).
- Typical columns include:
- listing_id – unique ID for each property
- host_id – unique ID for each host
- neighbourhood – area where the property is located
- room_type – type of listing (Entire home, Private room, etc.)
- price – cost per night
- availability_365 – number of days available per year
- reviews_per_month – guest reviews frequency

Note: A sample SQL script and CSV file is provided to import the dataset into MySQL.

## Learning Objectives:
By completing this exam, students should be able to:
- Demonstrate understanding of SQL theory and relational database design.
- Write queries to retrieve, manipulate, and analyze structured data.
- Apply aggregation, filtering, and joining techniques to solve real-world problems.
- Optimize SQL queries for performance considerations.

## Setup Instructions:
- Install recent version of MySQL.
- Import the provided dataset
- SOURCE airbnb_dataset.sql;
- Ensure the database is running and accessible.
- Use your preferred SQL client (MySQL Workbench).

## Usage
- Open the SQL exam paper (provided as .sql).
- For theory questions which are multiple choice, write answers in the provided space.
- For practical questions, execute queries in your SQL environment.
- Submit both your written answers and SQL scripts/results as instructed.

## Contributors
1. Hope Mohola
2. Bonakele Mdletshe
3. Melokuhle Makhwasa
4. Thato Mzilikazi
5. Nombulelo Tracy

## License
This project uses open-source Airbnb data. Content is intended for educational purposes only.
