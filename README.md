# 📚 ImmverseAI Power BI Project

## 📌 Overview
This project analyzes and visualizes book datasets using **Power BI**.  
The data comes from multiple sheets (`Main file`, `DimSheet1`, `DimSheet2`, `DimSheet3`) that include information about books, authors, publishers, languages, and publishing details.  

The goal is to clean, transform, and model the data to create **KPIs and interactive dashboards** for insights.

---

## 🚀 Process

### 1. Data Import
- Imported dataset from **`ImmverseAI_Task_Dataset.xlsx`** into Power BI.

### 2. Data Transformation (Power Query)
- Standardized column names (`Book_ID` → `book_id`, etc.).
- Replaced inconsistent values (`unknown` → `Unknown`).
- Removed damaged/irrelevant rows.
- Cleaned and standardized **Author, Publisher, Language** columns.
- Split **Language column** by comma, unpivoted for analysis.
- Replaced special characters (`e_Gangotri` → `eGangotri`).
- Converted NaN values → `Unknown`.
- Capitalized book names for consistency.

### 3. Data Modeling
- Built relationships between `Main file`, `DimSheet1`, `DimSheet2`, and `DimSheet3`.
- Star schema modeling with fact & dimension tables.

### 4. KPIs Created
- 📅 **Books by Day / Month / Week**
- 📖 **Total number of pages per book**
- 🏢 **Number of Publishers & Top Publishers**
- ✍️ **Unique Authors**
- 🌐 **Unique Languages & Most Common Language**
- 📆 **Oldest & Newest Publishing Year**
- 🔢 **Books Published per Year**
- 🎛️ **Language Slicer** (handles multiple languages per row)

### 5. Visualizations
- Line/Bar charts → **Books Published by Month/Year**
- Pie chart → **Language Distribution**
- Card visuals → **Total Books, Unique Authors, Publishers, Languages**
- Slicers → **Filter by Language, Publisher, Author**

---

## 📊 Key Learnings
- Cleaning **multi-language columns** with split + unpivot.
- Handling missing/dirty publishing data.
- Designing **effective KPIs** in Power BI.
- Creating **interactive dashboards** with slicers & filters.

---

## 📂 Files in Repository
- `ImmverseAI_Task_Dataset.xlsx` → Source dataset  
- `PowerBI_Process_Documentation.pdf` → Detailed process documentation  
- `README.md` → GitHub project summary  

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **Excel (for dataset inspection)**
- **DAX (for KPIs & Measures)**

---

## 📸 Screenshots
<img width="1148" height="645" alt="daashboard" src="https://github.com/user-attachments/assets/64963a97-8d6d-462a-9cd5-773d75d24bd6" />


---

## 👨‍💻 Author
**Adarsh**  
📧gmail:- wahewaladarsh8487@gmail.com
linkedin:- https://www.linkedin.com/in/adarshwahewal
Githiub:-   https://github.com/adarshwahewal
