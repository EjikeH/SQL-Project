#  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" title="MySQL-For Backend" /></a> SQL-Project
# 🛠️ DSQL & Relational Databases

This repository contains my SQL-based classwork and research from Week 3 of the Data Technician course. It demonstrates my understanding of core relational database concepts, SQL syntax, and the ability to apply database theory to real-world business scenarios.

---

## 📚 Topics Covered

### ✅ Day 1: Database Fundamentals
- Differences between **primary**, **secondary**, and **foreign** keys
- Examples of **one-to-one**, **one-to-many**, and **many-to-many** relationships
- Comparison between **relational** and **non-relational** databases
- Use cases for NoSQL vs. SQL

### ✅ Day 3: SQL JOIN Types (with examples)
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN
- SELF JOIN
- CROSS JOIN

---

## 💻 Day 4: SQL Practical Tasks

Using the `world_db` dataset, I answered various business-driven SQL scenarios including:

| Scenario | SQL Topic |
|----------|-----------|
| Count of US Cities | `COUNT + WHERE` |
| Highest Life Expectancy Country | `ORDER BY + LIMIT` |
| Cities with 'New' in Name | `LIKE` |
| Top 10 Most Populous Cities | `ORDER BY + LIMIT` |
| Cities with Population > 2M | `WHERE >` |
| Cities Starting with 'Be' | `LIKE 'Be%'` |
| Cities Between 500K–1M Pop. | `BETWEEN + ORDER` |
| City Name Frequency | `GROUP BY + COUNT` |
| Most & Least Populated Cities | `ORDER BY + LIMIT` |
| Capital City of Spain | `SUBQUERY` |
| Cities in Europe | `JOIN + WHERE` |
| Average Country Populations | `GROUP BY + AVG` |
| Capital City Population Comparison | `JOIN + ORDER` |
| Countries by Low Population | `ORDER ASC` |
| GDP Per Capita by City | `JOIN + Calculation` |
| Cities Ranked 31–40 by Population | `ROW_NUMBER()` |

Each task includes:
- 🔍 Problem Scenario
- ✅ SQL Syntax
- 📤 Output (where applicable)

---

## 📝 Optional Essay: Designing a Database for a Retail Business

Wrote a 500-word essay on:
- Understanding business requirements
- Structuring a schema for products, customers, sales, and loyalty programs
- SQL examples for `CREATE TABLE`, `INSERT`, and `FOREIGN KEY` usage
- Best practices for maintenance, backups, and scalability

This simulates a real-world database design project for a local convenience store.

---

## 🔧 Tools Used
- SQL (MySQL/PostgreSQL compatible syntax)
- `world_db` open dataset
- Microsoft Word for documentation

---

## 📂 Files Included
- `Data_Technician_Workbook_Week_3.docx`: Complete workbook with theory, queries, and essay.
- *(You can include `.sql` files or `.pdf` exports if desired)*

---

## 💡 Key Learnings
- Writing and optimizing SQL queries for real-world use
- Structuring normalized relational databases
- Applying business logic to database design
- Communicating technical work through written documentation

---

## 📌 Next Steps
- Build a local instance of the `world_db` and practice advanced queries
- Upload `.sql` scripts for reusable queries
- Convert written essay into a sample system architecture diagram
