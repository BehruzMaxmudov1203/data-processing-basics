<!-- Banner Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=6C5CE7&center=true&vCenter=true&width=900&lines=📂+Data+Processing;📁+Files+%26+Databases;💻+Python+SQL;📋+Jupyter+Notebooks" alt="Typing SVG" />
</p>

---

# 🚀 Data Processing: Files & Databases

This module covers **file handling, web data extraction, JSON/API processing, and database operations** in Python. It includes practical exercises with **Jupyter Notebooks**.

---

## 🧩 Module Structure

| Section | Description |
|---------|-------------|
| 10.1 | Introduction |
| 10.2 | Reading from a file |
| 10.3 | Writing to a file |
| 10.4 | HDF5 format |
| 10.5 | Reading & writing HDF5 (practical) |
| 10.6 | 📋 Jupyter Notebook: Files |
| 10.7 | Reading from web pages |
| 10.8 | Reading JSON and APIs |
| 10.9 | What is an API? |
| 10.10 | What is JSON? |
| 10.11 | Web/JSON/API practical exercise |
| 10.12 | 📋 Jupyter Notebook: Web & JSON |
| 10.13 | Databases: Introduction |
| 10.14 | SQL: Introduction |
| 10.15 | 🔗 SQL lesson link |
| 10.16 | Connecting to SQLite |
| 10.17 | Reading table into DataFrame |
| 10.18 | Sorting (ORDER BY) & DISTINCT |
| 10.19 | Filtering (WHERE) |
| 10.20 | 📋 Jupyter Notebook: SQLite |
| 10.21 | Exporting DataFrame to SQL table |
| 10.22 | Creating SQL table & inserting data |
| 10.23 | Updating & deleting SQL table |
| 10.24 | Writing SQL commands with f-strings |
| 10.25 | Final practical exercise (module) |
| 10.26 | 📋 Jupyter Notebook: SQLite Part 2 |
| 10.27 | Useful SQL commands |
| 10.28 | BETWEEN, IN & LIKE |
| 10.29 | 📋 Jupyter Notebook: SQLite Part 3 |

---

## 🛠 Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BehruzMaxmudov1203&show_icons=true&theme=tokyonight" alt="GitHub Stats" /> 
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=BehruzMaxmudov1203&theme=tokyonight" alt="GitHub Streak" /> 
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=BehruzMaxmudov1203&theme=react-dark" alt="GitHub Activity Graph" /> 
</p>

---


<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=FF6F61&center=true&vCenter=true&width=800&lines=SQL+Advanced+Filtering;BETWEEN+IN+LIKE;Filter+data+effectively" alt="Typing SVG" />
</p>


```sql
-- BETWEEN: select values within a range
SELECT * FROM employees
WHERE salary BETWEEN 3000 AND 5000;

-- IN: select multiple specific values
SELECT * FROM employees
WHERE department IN ('HR', 'IT', 'Sales');

-- LIKE: pattern matching
SELECT * FROM employees
WHERE name LIKE 'J%';  -- Names starting with J
