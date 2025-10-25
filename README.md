# Netflix Data Analysis Using SQL

# Overview
This project performs in-depth data analysis on Netflix’s content library using SQL to uncover trends, patterns, and insights about movies and TV shows. The dataset includes details such as title, cast, director, country, release year, rating, duration, and genre.

# Key Features & Insights

Content Classification: Counted and compared the number of Movies vs TV Shows on Netflix.
Rating Trends: Identified the most common rating across both content types.
Year & Country Analysis: Extracted top-producing countries, content released per year, and recent 5-year additions.
Genre & Duration Insights: Analyzed genre distribution, longest movie, and TV shows with more than 5 seasons.
Director & Actor Analysis: Filtered shows by specific directors (e.g., Rajiv Chilaka) and actors (e.g., Salman Khan), including top 10 Indian actors by content count.
Sentiment Categorization: Classified content as ‘Good’ or ‘Bad’ based on keywords like ‘kill’ and ‘violence’ in the description field.
Data Cleaning & Normalization: Utilized functions like UNNEST, STRING_TO_ARRAY, and SPLIT_PART to handle multi-valued columns such as country, cast, and genre.

# Tech Stack
Language: SQL (PostgreSQL / MySQL compatible)
Dataset: Netflix Titles Dataset
Tools: pgAdmin / MySQL Workbench
