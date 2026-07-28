# 📚 Student Performance & Attendance Analysis

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Project Overview

This project analyses student academic performance and attendance patterns to surface actionable insights for institutional decision-making. Built a **Project** with the Python Libraries, it covers the complete data analysis workflow — from raw data cleaning to management-ready visualisations.

---

## 🎯 Objectives

- Merge and clean marks and attendance datasets
- Engineer meaningful features (weighted score, attendance %, performance category)
- Identify at-risk students based on attendance and performance thresholds
- Deliver management-ready visualisations and MIS-style reports

---

## 📊 Dataset

- **Source:** Two CSV files — `Marks.csv` and `Attendance.csv`
- **Merged on:** Student Name
- **Assessments:** Mini Test 1, Mini Test 2, Live Test, Assignment
- **Attendance:** Daily records encoded as Y/N → 1/0

---

## ⚙️ Feature Engineering

| Feature | Description |
|---------|-------------|
| Total Marks | Sum of all 4 assessment scores |
| Percentage Marks | Total marks as % of maximum possible |
| Attendance % | Mean of daily attendance records × 100 |
| Weighted % | Attendance (40%) + Mini Tests (20%) + Live Test (20%) + Assignment (20%) |
| Category | Excellent (≥85%), Good (≥71%), Average (≥50%), Needs Improvement (<50%) |

---

## 🔍 Key Analysis

- **At-risk identification** — students with attendance below 75% but weighted score above 50%
- **Top performers** — top 3 students ranked by percentage marks
- **Attendance vs performance correlation** — impact of attendance on overall weighted score

---

## 📈 Visualisations

| Chart | Purpose |
|-------|---------|
| Bar Chart | Top 5 students by weighted % |
| Pie Chart | Distribution across 4 performance categories |
| Box Plots | Spread and outliers in each assessment |
| Bar Chart | Students with attendance below 50% |
| Correlation Heatmap | Relationship between assessments and attendance |

---

## 🗂️ Project Structure

Student-Performance-and-Attendance-Analysis/
├── Anirban Ray_Student Performance and Attendance Analysis.ipynb
├── Marks.csv
├── Attendance.csv
└── README.md

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.12 | Core language |
| Pandas | Data loading, merging, cleaning, transformation |
| Matplotlib | Bar charts, pie charts, box plots |
| Seaborn | Heatmap, styled visualisations |

---

## 💡 Business Insights

- Students with attendance below 75% show significantly lower weighted scores
- Performance category distribution reveals the proportion of students needing academic intervention
- Correlation heatmap identifies which assessments have the strongest impact on overall performance
- At-risk student list enables faculty to intervene early before final examinations

---

## 👤 Author

**Anirban Ray**
- 💼 [LinkedIn](https://linkedin.com/in/anirban-ray05)
- 🐙 [GitHub](https://github.com/anirray346)
