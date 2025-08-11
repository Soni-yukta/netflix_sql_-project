# 📊 Netflix Data Analysis using PostgreSQL

## 📌 Project Overview
This project performs an in-depth analysis of Netflix content using SQL queries in PostgreSQL.  
It answers **15 real-world business problems** related to movies and TV shows, ratings, genres, actors, and content trends.  
The dataset includes details such as title, type, director, cast, country, date added, release year, rating, duration, genres, and description.

---

## 🎯 Objectives
- Analyze content distribution by type, genre, and rating.
- Identify top-performing actors and directors.
- Track year-wise and country-wise trends in content addition.
- Find longest-running movies and popular multi-season TV shows.
- Classify content as **Good** or **Bad** based on keywords.
- Extract meaningful insights using advanced SQL concepts.

---

## 🛠️ Tools & Technologies
- **Database:** PostgreSQL
- **SQL Functions Used:** 
  - Aggregations (`COUNT`, `GROUP BY`, `HAVING`)
  - String functions (`STRING_TO_ARRAY`, `UNNEST`, `SPLIT_PART`, `TRIM`)
  - Date functions (`TO_DATE`, `EXTRACT`, `CURRENT_DATE`, `INTERVAL`)
  - Conditional logic (`CASE`, `ILIKE`)
  - Window functions (`RANK() OVER (...)`)
  - Common Table Expressions (CTEs)

---

## 📂 Business Problems Solved
1. Count the number of movies and TV shows.
2. Find the most common rating for each content type.
3. List movies from a specific year.
4. Identify top 5 countries with the most content.
5. Find the longest-running movie.
6. Get content added in the last 5 years.
7. List all movies/TV shows by a specific director.
8. Find TV shows with more than 5 seasons.
9. Count the number of items in each genre.
10. Find yearly average content release by India and top 5 years.
11. List all documentaries.
12. Find all content without a director.
13. Find movies by a specific actor in the last 10 years.
14. Identify top 10 actors in India by content count.
15. Categorize content as Good or Bad based on keywords.

---

## 📸 Example Insights
- **Drama** and **International Movies** are the most frequent genres.
- India shows a spike in Netflix content releases after 2018.
- Certain actors dominate regional Netflix content.
- Keyword-based filtering helps identify violent content.

---

## 🚀 How to Run
1. Install **PostgreSQL** on your system.
2. Create a database and import the Netflix dataset.
3. Run the queries from `NETFLIX PROJECT SOLUTION.sql`.
4. Explore and modify queries to derive new insights.

---

## 📜 License
This project is for educational and analytical purposes.  
Dataset credit goes to the respective data provider.

---

## 👩‍💻 Author
**Yukta Soni**  
Data Science & Analytics Enthusiast
