# 🎬 Movies Analysis | SQL Project

This project performs in-depth SQL-based analysis on the MovieLens dataset — a popular dataset containing millions of movie ratings, tags, and metadata. The analysis spans beginner to advanced levels, covering SQL queries, views, CTEs, stored procedures, and window functions.

---

## ⭐ Features

- Dataset setup and table creation using PostgreSQL
- Designed 30+ custom SQL questions across beginner, intermediate, and advanced levels
- Dataset setup and table creation using PostgreSQL
- Imported and managed 1.5+ GB of real-world movie rating data from MovieLens
- Performed genre classification, tag relevance analysis, and user behavior insights
- Implemented views, stored procedures, window functions, and recursive CTEs
- Wrote optimized queries with `EXPLAIN ANALYZE` for performance evaluation
- Simulated ACID transactions and used temporary/materialized views for advanced use cases

---

## 🛠 Technologies Used

| Tool/Service | Purpose |
|--------------|---------|
| [Kaggle](https://www.kaggle.com/) | Dataset exploration |
| [PostgreSQL](https://www.postgresql.org/) | Database management |
| [pgAdmin 4](https://www.pgadmin.org/) | GUI for database operations |

---

## ⚙️ How It Works

1. 📥 Downloaded data from [MovieLens](https://grouplens.org/datasets/movielens/latest/)
2. 🗃 Created database and tables using PostgreSQL
3. 📌 Imported CSV data (~1.5 GB) via pgAdmin 4
4. 🔎 Executed 30+ SQL queries across 3 difficulty levels
5. 🧠 Created views, functions, materialized views, and CTEs
6. 📈 Extracted insights on movie trends, top genres, user behavior, and tag relevance

---

## 🔍 Preview

📄 [Click here to view the full project log (PDF)](./Project_log.pdf)

---

## 📁 Folder Structure
```
MoviesAnalysisSQL/
├── Project_log.pdf
├── Questions.md
└── README.md
```

---

## 💡 Use Cases

- 📊 Analyzing user behavior through ratings and tags
- 🎯 Finding most rated or top-rated movies by genre
- 🧬 Working with tag genome and relevance analysis
- 🏗 Practicing SQL queries from beginner to advanced levels
- 🧪 Demonstrating database normalization and function creation
- 📚 Building a PostgreSQL portfolio project

---

## 🧰 Setup Instructions

1. Install PostgreSQL and pgAdmin 4
2. Download dataset from: [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/)
3. Run the SQL scripts from the project log to create tables
4. Import CSV files into respective tables (Format: CSV, Encoding: UTF-8)
5. Run the SQL queries as per your learning phase (Beginner → Advanced)

---

## 📝 Notes

- The dataset includes **33,832,162 ratings** and **2,328,315 tag applications** for **86,537 movies**
- User and movie IDs are **anonymized** and consistent across all files
- Ratings are made on a **0.5–5.0 star scale**; genres are **pipe-separated** (e.g., Action|Adventure|Sci-Fi)
- All files are encoded in **UTF-8** — ensure correct encoding during import in pgAdmin
- Timestamps are stored in **UNIX format** (seconds since January 1, 1970 UTC)

---

## 🙋‍♀️ Author

**Anushka Sharma**  
🌐 [LinkedIn](https://www.linkedin.com/in/anushkasharma008/) • 🐱 [GitHub](https://github.com/Anushka-Sharma-008) 
🎓 Learning Data Science, Analytics & Machine Learning

---

## ⭐ Show Your Support

If you found this project helpful or inspiring:

- ⭐ Star this repository  
- 🛠️ Fork it to build upon or adapt it for your own use  
- 💬 Share feedback or suggestions via Issues/Discussions
