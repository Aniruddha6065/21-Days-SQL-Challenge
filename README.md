<div align="center">

<img src="https://svg-banners.vercel.app/api?type=glitch&text1=21%20DAYS%20SQL%20🚀&text2=Beginner%20→%20Advanced&width=800&height=250" alt="21 DAYS SQL Challenge: Beginner to Advanced Banner" />

<br>

[![Challenge](https://custom-icon-badges.demolab.com/badge/Challenge-21%20Days-4169E1?style=for-the-badge&logo=calendar&logoColor=white)](http://indiandataclub.com/)
[![Status](https://custom-icon-badges.demolab.com/badge/Status-In%20Progress-success?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com/NihalMishra01/21-Days-SQL-Challenge)
[![Day](https://custom-icon-badges.demolab.com/badge/Day-2%2F21-orange?style=for-the-badge&logo=flame&logoColor=white)](https://github.com/NihalMishra01/21-Days-SQL-Challenge/tree/main)
[![SQL](https://custom-icon-badges.demolab.com/badge/SQL-Database-blue?style=for-the-badge&logo=database&logoColor=white)](https://en.wikipedia.org/wiki/SQL)

<br>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=4169E1&center=true&vCenter=true&random=false&width=500&lines=Learning+SQL+Daily+💪;Building+Real+Projects+🎯;Mastering+Data+Analysis+📊" alt="Typing SVG: Learning SQL Daily, Building Real Projects, Mastering Data Analysis" />

<br>

[**🔥 View Challenge**](http://indiandataclub.com/) • [**💼 LinkedIn**](https://www.linkedin.com/in/nihalmishra01) • [**🐛 Report Bug**](https://github.com/NihalMishra01/21-Days-SQL-Challenge/issues)

</div>

---

## 📖 About The Challenge: SQL Mastery in 21 Days

I'm undertaking the **21-Days SQL Challenge** organized by [**Indian Data Club**](http://indiandataclub.com/) to master **SQL from ground zero to an advanced level**. This repository is a complete documentation of my daily progress, code solutions, and key learnings, shared publicly for accountability and collaboration.

> **🎯 Mission:** Build production-ready SQL skills through consistent daily practice, real-world datasets, and rigorous problem-solving.

### ⚙️ Challenge Structure at a Glance

| Aspect | Details |
| :--- | :--- |
| **Duration** | 21 consecutive days |
| **Daily Commitment** | 1-2 hours of focused learning |
| **Key Topics** | Queries, Joins, Subqueries, **Window Functions**, CTEs, Optimization, Data Modeling |
| **Practice** | Real-world datasets with industry-standard problems |
| **Target Roles** | Data Analyst, Data Engineer, Data Scientist, Backend Developer |

---

## 💡 Why This Challenge? The Data Foundation

> **SQL is the fundamental language of data-driven careers.**

* ✅ **Most In-Demand Skill:** Essential for 90%+ of data analyst positions.
* ✅ **Universal Language:** Works across all major databases (PostgreSQL, MySQL, SQL Server, etc.).
* ✅ **AI/ML Prerequisite:** Critical for cleaning and preparing data for advanced models.
* ✅ **Business Intelligence:** Necessary for all analytics, reporting, and dashboarding.

### **My Learning Goals:**
* ✍️ Write **optimized queries** for large datasets.
* 🧠 Master complex **joins and subqueries**.
* 🏛️ Understand database **design principles**.
* 🛠️ Build **real-world data analysis** projects.
* Interview **preparation** for technical SQL rounds.

---

<div align="center">

## 📊 Challenge Statistics

| Metric | Count |
| :--- | :--- |
| 📝 **Days Completed** | **2** / 21 |
| ✅ **Problems Solved** | **16** |
| 📁 **Files Uploaded** | 2 |
| ⏱️ **Total Hours** | 4 |
| 🔥 **Current Streak** | **2** days |

**Progress Bar:**
[██░░░░░░░░░░░░░░░░░░] **9.52% Complete**

</div>

---

### 🔥 Day 2: Advanced Filtering & Logical Operators (Current Day)
**📆 Date:** November 4, 2025  
**⏱️ Time Invested:** 2 hours  
**📂 File:** [Day2 SQL Challenge.sql](https://github.com/NihalMishra01/21-Days-SQL-Challenge/blob/main/Day2%20SQL%20Challenge.sql)

#### **📚 Topics Mastered**
* **Advanced WHERE:** Using logical operators (**AND, OR, NOT**).
* **Range & Set Operators:** The **IN** operator for multiple values and **BETWEEN** for inclusive ranges.
* **Pattern Matching:** The **LIKE** operator with wildcards (`%`).
* **Sorting:** Using **ORDER BY** for structured results.

#### **🏥 Practice Dataset: Hospital Management System**
The challenge continued with the Hospital Management System, introducing the **`staff`** and **`staff_schedule`** tables to practice cross-table filtering.

#### **✅ Problems Solved (9/9)**
| # | Problem | Concept | Status |
| :--- | :--- | :--- | :--- |
| Q1 | Staff in surgery or general\_medicine | **IN** operator (Clean filtering) | ✅ |
| Q2 | Patients with satisfaction between 70-90 | **BETWEEN** operator (Inclusive range) | ✅ |
| Q3 | Patients arrived after date in Emergency | **WHERE with AND** (Combined conditions) | ✅ |
| Q4 | Weeks with refused > 50 **OR** morale < 60 | **OR** operator (Alternative conditions) | ✅ |
| Q5 | Patients name starts with 'A', NOT emergency | **LIKE with AND** (Pattern matching & exclusion) | ✅ |
| Q6 | List all patients who belong to ICU service | Simple filtering | ✅ |
| Q7 | Find patients whose age is greater than 60 | WHERE with comparison | ✅ |
| Q8 | Show staff members whose role is Doctor | Role-based filtering | ✅ |
| Q9 | Get records where available beds < 20 | Numerical comparison | ✅ |

#### **💡 Key Takeaways**
> **"Mastering logical operators is the key to writing powerful and efficient SQL queries."**
* The **IN** operator is generally **cleaner and more efficient** than multiple `OR` conditions.
* Be mindful of using the `%` wildcard with **LIKE**, as it can lead to **full table scans** on very large, unindexed columns.

---

### 🔙 Day 1: SQL Fundamentals & Data Retrieval
**📆 Date:** November 3, 2025  
**⏱️ Time Invested:** 2 hours  
**📂 File:** [Day1 SQL Challenge.sql](https://github.com/NihalMishra01/21-Days-SQL-Challenge/blob/main/Day1%20SQL%20Challenge.sql)

#### **📚 Topics Learned**
* **DDL:** **CREATE TABLE** with constraints (**PRIMARY KEY**).
* **DML:** **SELECT** (all columns vs. specific columns).
* **Filtering:** The basic **WHERE** clause.
* **Data Manipulation:** **DISTINCT** for unique values and **LIMIT** for pagination.

#### **💡 Key Takeaways**
> **"The foundation of great queries starts with understanding your data structure."**
* Always specify columns instead of `SELECT *` in production code for better **performance and clarity**.
* Proper data type and table design is essential to prevent downstream data issues.

---

## 🛠️ Tech Stack & Repository Structure

### **Environment & Tools**
<div align="center">

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)

</div>

### **File Structure**
| File/Folder | Description |
| :--- | :--- |
| 📄 `README.md` | Complete project documentation (You are here!) |
| 📜 `Day1 SQL Challenge.sql` | Day 1 solutions and SQL code |
| 📜 `Day2 SQL Challenge.sql` | **Day 2 solutions and SQL code** |
| ... | Upcoming daily challenge files (Days 3-21) |
| 📊 `datasets/` | Practice datasets (CSV files used for loading) |

---

## 🤝 Connect & Collaborate

I'm documenting this journey publicly on **LinkedIn** and welcome connections, feedback, and discussion!

<div align="center">

### **Let's Connect!**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nihalmishra01)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NihalMishra01)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nihalmishraaofficial@gmail.com)

</div>

**Open to:**
* 💬 **SQL discussions** and doubt-clearing.
* 📢 **Feedback** on my daily solutions and code optimization.
* 🌐 **Networking** with fellow data professionals and enthusiasts.

---

## 💪 Motivation & Accountability

> *"The expert in anything was once a beginner. The key is to start and stay consistent."*

**This Public Challenge is for:**
* 📢 **Accountability** through transparency.
* 🌱 **Learning through teaching** (Feynman Technique).
* 💼 **Showcasing commitment** and skill development to employers.

---

<div align="center">

### ⭐ If you find this helpful, please consider giving it a star!

**Let's master SQL together, one query at a time!** 

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=NihalMishra01.21-Days-SQL-Challenge)

</div>
