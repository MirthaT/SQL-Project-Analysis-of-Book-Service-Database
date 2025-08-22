# 📚 SQL Case Study – Book Ratings Database

## 📌 Project Overview
During the COVID-19 pandemic, many people turned to reading as a primary source of entertainment at home. This trend led to the emergence of book-focused digital platforms.

In this project, I analyzed a simulated SQL database from a fictional book service. The dataset includes information on books, authors, publishers, user ratings, and reviews. The goal was to extract insights to support the value proposition of a new product in this market.


## 🧩 Objectives

The following analytical questions were answered using SQL:

- 📅 Count how many books were published after January 1, 2000  
- ⭐ Find the number of reviews and the average rating per book  
- 🏢 Identify the publisher with the most books over 50 pages  
- 🖋️ Find the author with the highest average rating (minimum 50 reviews per book)  
- 🧑‍💻 Calculate the average number of text reviews by users who rated more than 50 books  

   
---

## 🔍 Summary of Insights

| Question                                         | Key Insight                                  |
|--------------------------------------------------|-----------------------------------------------|
| Books after 2000                                 | 📚 **819** books published after 01/01/2000   |
| Publisher with most full-length books (>50 pages)| 🏢 **Penguin Books** (42 titles)              |
| Top-rated author (min. 50 reviews per book)      | 🖋️ **Diana Gabaldon**, avg. rating: **4.3**   |
| Avg. text reviews by active users (>50 ratings)  | 💬 **24.33** reviews per user on average      |

---
## 🗂️ Project Structure

SQL-Project-Analysis-of-Book-Service-Database/
│
├── SQL.ipynb # Main analysis in Jupyter Notebook
├── README.md # Project summary and instructions
├── queries.sql # (Optional) SQL script with all queries
└── images/ # (Optional) Screenshots or visuals

---

## ⚙️ How to Run the Notebook

1. Clone the repository  
2. Install required libraries:
    ```bash
    pip install pandas sqlalchemy psycopg2
    ```
3. Update the database credentials in the notebook  
4. Run each cell step-by-step in Jupyter

---
   
## 💻 Tools & Technologies

- **PostgreSQL**
- **SQLAlchemy + Psycopg2**
- **Jupyter Notebook**
- **Python + Pandas**

---

## 📌 Status

✅ Completed  
🚀 Open to feedback and improvements!

---

## 👩‍💻 Author

**Mirtha Torres**  
_Data Analyst | IT Support | SQL Enthusiast_  
🔗 [GitHub Profile](https://github.com/MirthaT)

