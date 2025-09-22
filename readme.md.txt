# 🎬 Netflix Dataset Cleaning – Task 1 (Data Analyst Internship)

## 📌 Task Overview
This project is part of the **Data Analyst Internship – Task 1: Data Cleaning and Preprocessing**.  
The objective is to clean a raw dataset by handling missing values, duplicates, inconsistent formats, and preparing it for further analysis.  

Dataset used: **Netflix Movies and TV Shows** (from Kaggle)

---

## 🛠 Steps Performed
1. **Checked working directory & verified dataset presence**  
2. **Explored dataset** – checked shape, missing values, and data types  
3. **Handled missing values**:  
   - Dropped rows where `title` was missing  
   - Filled missing values in `director`, `cast`, `country`, `date_added`, and `rating` with `"Unknown"`  
4. **Removed duplicates** using `.drop_duplicates()`  
5. **Standardized column names** – lowercase, snake_case format  
6. **Standardized text values** – e.g., `country` names formatted consistently  
7. **Fixed data formats**:  
   - Converted `date_added` to datetime  
   - Converted `release_year` to integer  
8. **Exported cleaned dataset** as `netflix_titles_cleaned.csv`  

---

## 📊 Summary of Changes
- **Initial Shape:** (7787, 12)  
- **Final Shape:** (after cleaning – fewer rows due to duplicate removal)  
- **Missing values handled:** replaced with `"Unknown"`  
- **Duplicates removed:** Yes  
- **Column names standardized:** Yes  
- **Date formats standardized:** Yes  
- **Data types fixed:** Yes  

---

## 📝 Interview Q&A (Based on Task)
Included in the Jupyter Notebook as Markdown cells:  
- Handling missing values  
- Duplicate treatment  
- Difference between `dropna()` and `fillna()`  
- Outlier treatment  
- Standardizing data  
- Handling inconsistent formats  
- Common data cleaning challenges  
- Checking data quality  

---

## 📂 Project Structure
Netflix_Data_Cleaning/
├── Netflix_Task1.ipynb # Jupyter Notebook with code + Q&A
├── netflix_titles.csv # Raw dataset (from Kaggle)
├── netflix_titles_cleaned.csv # Cleaned dataset (output)
└── README.md # Project summary

## 🚀 How to Run
1. Open Jupyter Notebook in this folder.  
2. Run `Netflix_Data_Cleaning_Task1.ipynb`.  
3. Make sure `netflix_titles.csv` is in the same directory as the notebook.  
4. The cleaned dataset will be saved as `netflix_titles_cleaned.csv`. 

 
