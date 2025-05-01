# 🎓 Student Exam Result Processing (C Mini Project)

A **C programming mini-project** developed to automate the processing of student exam results for an educational institution.  
This console-based application emphasizes core programming principles like **input validation**, **loops**, and **data analysis**.

---

## 📖 Overview

This project allows users to enter marks for multiple students across several subjects, then calculates and displays detailed result statistics for each student and the overall class performance.

---

## 🎯 Key Features

- 🧑‍🎓 **Dynamic Student & Subject Entry:**  
  Accepts user-defined number of students and subjects.

- ✅ **Input Validation:**  
  - Ensures positive values for number of students and subjects.  
  - Validates marks are within the **0 - 100** range.

- 📊 **Per-Student Results:**  
  - Calculates total and average marks.  
  - Counts passed and failed subjects per student.  
  - Marks a subject as **passed** if score ≥ **35**.  
  - A student **passes overall** if their average ≥ **30%**.

- 🏆 **Class Performance Summary:**  
  - 📈 Overall class average  
  - 🥇 Highest average score  
  - ✔️ Number and percentage of passed students  
  - ❌ Number and percentage of failed students

---

## 🛠️ Built With

- 📘 C Programming Language
- 🖥️ Console Interface (Standard Input/Output)

---

## 🧪 Concepts Practiced

- Arrays
- Nested loops
- Functions
- Conditional logic
- Aggregation and percentage calculations
- Input validation and error handling

---

## 🚀 How to Run

1. Open the project in a C IDE (e.g., Code::Blocks, Dev C++, or Visual Studio)  
   **OR** use a terminal with GCC compiler.

2. Compile the file:
   ```bash
   gcc student_results.c -o student_results
