# Deloitte-Data-Analytics-Internship

# ⚖️ Employee Equality Analysis & Workplace Risk Visualization

This project focuses on identifying harmful patterns in employee compensation equality and visualizing those patterns to support fair and safe workplaces. The project includes data classification using Excel and dynamic visualizations with Tableau.

---

## 🧾 Project Summary

We analyzed compensation equality scores across multiple factories and job roles. The aim was to detect patterns of potential harm, unfair treatment, and discrimination—especially roles or departments that may need HR attention.

---

## ✅ Tasks Overview

### 🛑 Task 1 – Visualization of Harmful Patterns (Tableau)

- **File**: `Book1.twbx`
- **Tool Used**: Tableau
- **Objective**: Identify and visualize factors that might indicate harmful or unfair conditions in the workplace.
  
#### 📊 Visualizations Include:
- **Heatmap of Discriminative Roles**: Highlights job roles with extreme negative equality scores.
- **Factory-Level Risk Dashboard**: Compares discrimination levels across factories.
- **Category Pie Chart**: Visualizes proportions of “Fair,” “Unfair,” and “Highly Discriminative” job roles.

> These insights can help management proactively reduce workplace inequality and improve employee well-being.

---

### 📄 Task 2 – Equality Score Classification in Excel

- **Input File**: `Task 2 Equality Table.xlsx`
- **Updated Output**: `Task 2 Equality Table - Updated.pdf`
- **Objective**: Classify each record based on the `Equality Score`.

#### 🔍 Classification Rules:
| Equality Score Range | Classification         |
|----------------------|------------------------|
| -10 to +10           | Fair                   |
| -11 to -20 / 11 to 20| Unfair                 |
| < -20 or > 20        | Highly Discriminative  |

- A new column `Equality Class` was created using Excel formula logic.
- This classification is used as the basis for visualization in Task 1.

---

## 🧰 Tools Used

- 📊 **Tableau Desktop/Public**
- 📗 **Microsoft Excel**

---

## 📁 File Structure

```bash
📦 Equality-Score-Project
├── 📄 Task 2 Equality Table.xlsx
├── ✅ Task 2 Equality Table - Updated.pdf
├── 📈 Book1.twbx
└── 📘 README.md
