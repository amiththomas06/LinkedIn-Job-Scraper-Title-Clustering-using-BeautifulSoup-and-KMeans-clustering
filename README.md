# 🔍LinkedIn-Job-Scraper-Title-Clustering-using-BeautifulSoup-and-KMeans-clustering

This project scrapes analyst-related job postings from LinkedIn, extracts structured job metadata, clusters job titles using natural language embeddings, and stores the results in a SQL Server database.

---

## 📌 Features

- Scrape LinkedIn jobs using title and location
- Extract job metadata (title, company, location, applicants, posted date)
- Encode job titles using SentenceTransformers
- Cluster job titles using KMeans
- Assign standardized job categories to clusters
- Store data in SQL Server using SQLAlchemy + pyodbc

---

## 🧪 Tech Stack

- Python
- BeautifulSoup
- Pandas
- SQLAlchemy
- pyodbc
- SentenceTransformers
- Scikit-learn

---

## ⚙️ How It Works

### 1. Scrape LinkedIn Jobs

```python
title = 'Analyst'
location = 'United Kingdom'
