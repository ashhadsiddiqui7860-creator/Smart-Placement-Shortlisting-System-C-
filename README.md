# 🚀 Smart Placement Shortlisting System (C++)

## 📌 Overview

This project is a **skill-based placement shortlisting system** built in C++.
It simulates how companies filter candidates using **skills, test scores, and academic performance**.

Instead of manual selection, the system automatically:

* Evaluates candidates
* Assigns scores
* Shortlists eligible candidates
* Ranks them efficiently

---

## 🎯 Features

### ✅ Candidate Management

* Add new candidates
* Store data using file handling
* Display all candidates

### 🧠 Smart Evaluation System

* Weighted scoring based on:

  * Academic Marks (50%)
  * Skills (30%)
  * Test Score (20%)

* Skill importance is predefined:

  * C++, DSA → High weight
  * HTML, CSS → Lower weight

---

### 🏆 Shortlisting Logic

* Candidate is **Shortlisted** if:

  * Final Score ≥ 80
  * Skill Score ≥ 40

Otherwise → Rejected

---

### 📊 Ranking System (Sorting)

* Candidates are sorted by **Final Score**
* Uses **STL sort()**
* Time Complexity: **O(n log n)**

---

### ⚡ Top K Candidates (Priority Queue)

* Displays top performers efficiently
* Uses **Max Heap (priority_queue)**
* Faster than sorting entire list

---

### 🔍 Skill-Based Search

* Search candidates by a specific skill
* Example:

  * Search “C++”
  * Displays all candidates having that skill

---

## 🛠️ Technologies Used

* C++
* STL (vector, map, priority_queue)
* File Handling (ifstream, ofstream)

---

## 🧮 DSA Concepts Used

| Concept        | Usage                 | Complexity     |
| -------------- | --------------------- | -------------- |
| Sorting        | Ranking candidates    | O(n log n)     |
| Priority Queue | Top K candidates      | O(n + k log n) |
| Linear Search  | Skill-based filtering | O(n)           |
| Map            | Skill weight lookup   | O(log n)       |

---

## 📂 File Structure

candidates.txt → Stores candidate data

---

## ▶️ How to Run

1. Compile:

```bash
g++ project.cpp -o project
```

2. Run:

```bash
./project
```

---

## 🧪 Sample Menu

```
===== Placement System =====
1 Add Candidate
2 Display Candidates
3 Sort Candidates
4 Show Shortlisted
5 Show Top K Candidates
6 Search by Skill
7 Exit
```

---

## 💡 Example Workflow

1. Add candidate:

   * Enter marks, skills, test score
2. System calculates:

   * Skill score
   * Final score
3. Candidate is:

   * Shortlisted / Rejected
4. Use:

   * Sort → full ranking
   * Top K → best candidates
   * Search → skill filtering

---

## 🏆 Why This Project is Unique

* Real-world placement simulation
* Skill-based intelligent filtering
* Combines **OOP + DSA + File Handling**
* Efficient algorithms used

---

## 🚀 Future Improvements

* Add candidate update/delete
* Company-specific job filtering
* GUI interface
* Database integration (MySQL)

---

## 👨‍💻 Author

Ashhad Siddiqui

---
