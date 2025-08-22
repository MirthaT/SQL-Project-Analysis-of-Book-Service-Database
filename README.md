# 📚 SQL Case Study – Book Ratings Database

## 📌 Project Overview
The COVID-19 pandemic shifted people’s lifestyles dramatically, leading many to spend more time at home engaging in activities like reading. This change created a surge in demand for book-related digital platforms.

This project explores a SQL database from a startup that serves book readers. The database includes information about books, authors, publishers, user ratings, and reviews. Our task is to perform analytical queries to extract meaningful insights that can inform business decisions for a potential new product in this space.

## 🧩 Objectives

The following analytical questions were answered using SQL:

1. How many books were published after January 1, 2000?
2. What is the number of reviews and the average rating for each book?
3. Which publisher has published the most books with more than 50 pages?
4. Who is the highest-rated author (only considering books with at least 50 ratings)?
5. What is the average number of text reviews written by users who have rated more than 50 books?

   
## 🗂 Dataset
The database contains five tables:

### `books`
| Column | Description            |
|--------|------------------------|
| book_id | Book ID               |
| author_id | Author ID           |
| title | Book title              |
| num_pages | Number of pages     |
| publication_date | Publication date |
| publisher_id | Publisher ID     |

### `authors`
| Column | Description            |
|--------|------------------------|
| author_id | Author ID           |
| author | Author's name          |

### `publishers`
| Column | Description            |
|--------|------------------------|
| publisher_id | Publisher ID     |
| publisher | Publisher name      |

### `ratings`
| Column | Description            |
|--------|------------------------|
| rating_id | Rating ID           |
| book_id | Book ID               |
| username | Reviewer username    |
| rating | Rating score (1-5)     |

### `reviews`
| Column | Description            |
|--------|------------------------|
| review_id | Review ID           |
| book_id | Book ID               |
| username | Reviewer username    |
| text | Review content           |


## 🔎 Tools Used

- SQL (PostgreSQL)
- Python (Pandas, SQLAlchemy)
- Jupyter Notebook

---

## 🧾 Summary of Insights

- A significant number of books were published after 2000, showing recent growth in digital publishing.
- Some authors consistently receive high ratings, indicating reader preference patterns.
- A few publishers dominate longer book publications, which may point to genre trends.
- Active users tend to engage more deeply, leaving both ratings and detailed reviews.

---

## 📌 Status

✅ Completed  
📁 Stored in: `/notebooks/sql_case_study_books.ipynb`

---

## 👩‍💻 Author

**Mirtha Torres**  
Data Analyst | IT Support Specialist  
🔗 [GitHub Profile](https://github.com/MirthaT)

