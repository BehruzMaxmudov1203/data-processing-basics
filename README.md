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
| Introduction | Overview of file handling and databases |
| Reading from a file | Learn how to read data from files |
| Writing to a file | Learn how to write data to files |
| HDF5 format | Introduction to HDF5 data format |
| Reading & writing HDF5 (practical) | Hands-on practice with HDF5 files |
| 📋 Jupyter Notebook: Files | Notebook exercises for file handling |
| Reading from web pages | Learn to extract data from web pages |
| Reading JSON and APIs | Learn to read JSON and interact with APIs |
| What is an API? | Explanation of API concepts |
| What is JSON? | Explanation of JSON format |
| Web/JSON/API practical exercise | Hands-on exercise using web, JSON, and API |
| 📋 Jupyter Notebook: Web & JSON | Notebook exercises for web and JSON |
| Databases: Introduction | Introduction to databases |
| SQL: Introduction | Basics of SQL |
| 🔗 SQL lesson link | Link to SQL lesson |
| Connecting to SQLite | Connecting Python to SQLite database |
| Reading table into DataFrame | Import SQL tables into Pandas DataFrame |
| Sorting (ORDER BY) & DISTINCT | SQL sorting and removing duplicates |
| Filtering (WHERE) | SQL filtering with WHERE clause |
| 📋 Jupyter Notebook: SQLite | Notebook exercises for SQLite |
| Exporting DataFrame to SQL table | Export Pandas DataFrame to SQL table |
| Creating SQL table & inserting data | Create tables and insert data in SQL |
| Updating & deleting SQL table | Update and delete SQL table entries |
| Writing SQL commands with f-strings | Dynamic SQL commands with Python f-strings |
| Final practical exercise (module) | Module-ending hands-on exercise |
| 📋 Jupyter Notebook: SQLite Part 2 | Part 2 of SQLite notebook exercises |
| Useful SQL commands | Important SQL commands summary |
| BETWEEN, IN & LIKE | SQL advanced filtering examples |
| 📋 Jupyter Notebook: SQLite Part 3 | Part 3 of SQLite notebook exercises |

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

<p align="center"> <img src="https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif" width="400" alt="SQL Animation"> </p>


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
