# 🎵 Chinook Music Store Data Analysis (SQL Project)

This project is a deep-dive SQL analysis of the **Chinook Database**, a digital music store that includes tables for artists, albums, media tracks, invoices, and customers. The goal of this project is to extract actionable business insights by answering a series of real-world queries using **SQL**.

---

## 🗂️ Project Overview

Using SQL queries, I explored the Chinook database to uncover insights into sales trends, customer behavior, top-performing artists, and genre popularity across countries. This analysis aims to answer key business questions such as:

- Who are our best customers?
- Which cities generate the most revenue?
- What genres are most popular by region?
- Which artists and songs drive the most sales?

All queries were executed using standard SQL and involved operations like JOINs, GROUP BY, aggregation functions, subqueries, and Common Table Expressions (CTEs).

---

## 📊 Key Business Questions Answered

1. **Who is the senior-most employee based on job title?**
2. **Which country has the most invoices?**
3. **What are the top 3 highest invoice totals?**
4. **Which city generated the highest total revenue?**
5. **Who is the best customer based on money spent?**
6. **Which customers listen to Rock music?**
7. **Top 10 artists based on number of Rock tracks produced**
8. **Tracks that are longer than the average track length**
9. **How much has each customer spent on top-selling artists?**
10. **Most popular music genre in each country (based on purchases)**
11. **Top-spending customer in each country**

---

## 📌 Tools & Technologies

- **SQL** (Standard SQL syntax)
- **Chinook Database** (SQLite-based music store schema)
- **pgAdmin / MySQL Workbench / SQL Server** (Any SQL GUI can be used)

---

## 📁 Dataset

- **Source:** Chinook sample database
- **Tables Used:** `customer`, `invoice`, `invoice_line`, `track`, `album`, `artist`, `employee`, `genre`

---

## 💡 Insights Gained

- The highest revenue comes from **specific cities**, which helps with **geo-targeted promotions**.
- **Rock music** dominates the genre, providing opportunities for **targeted artist collaborations**.
- **Customer spending patterns** reveal potential high-value markets.
- **Top artists** by track count and sales inform strategic **music promotions**.

---

## 📌 How to Use

To replicate this project:

1. Download and install any SQL environment (e.g., SQLite, MySQL, PostgreSQL).
2. Import the Chinook database.
3. Copy and execute the queries from the project SQL file.

---


