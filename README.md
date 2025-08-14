# 🐼 AICP Internship – Week 2: Pandas Exercises

This repository contains solutions to **Pandas practice exercises** completed as part of the **Artificial Intelligence Community of Pakistan (AICP)** internship program.

---

## 📝 Task Overview
Pandas is a powerful Python library for data manipulation and analysis, built on top of NumPy.  
This week’s exercises focused on **Series**, **DataFrames**, data indexing, importing/exporting CSV & Excel files, and performing basic statistics.

---

## 📂 Exercises
1. **Create a Pandas Series** without using a dictionary.
2. **Create a Pandas Series** using a dictionary.
3. **Create a Pandas DataFrame** from a Python dictionary.
4. **Replace DataFrame index** with `['a','b','c','d','e','f']`.
5. **Calculate mean, maximum, and minimum** for the label “temperature”.
6. **Import CSV (`people.csv`)** with:
   - Specific columns: `["First Name", "Sex", "Email", "Phone", "Job Title"]`
   - Set `["Sex", "Job Title"]` as index
   - Skip rows `[1, 5]`
   - Export as `NewPeople.csv`
7. **Import Excel sheet (`SampleWork.xlsx`)**:
   - Import only first and last column from sheet 1
   - Skip row 2
   - Set row 2 as header
   - Export as a new sheet
8. **Create DataFrame (`AICP_DF`)** and perform:
   - Select `'Name'` & `'Qualification'` → save to `df1`
   - Add column `"Height"` with values `[5.1, 6.2, 5.1, 5.2, 5.1]`
   - Set `"Name"` as index
   - Retrieve row with index `"Hifza"`
   - Retrieve row with index `3`
   - Drop row with index `"Bilal"`

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy

---

## 🚀 How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/malik8154/AICP-Internship-Week2-Pandas-Exercises.git
   cd AICP-Internship-Week2-Pandas-Exercises
