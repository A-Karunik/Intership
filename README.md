# Intership

# 🎬 Netflix Titles Data Cleaning

This project focuses on cleaning and preparing the Netflix Titles dataset for analysis using Python and Pandas. It was implemented in Google Colab.
---
## 📂 Dataset
- **Source**: [Netflix Titles dataset](https://www.kaggle.com/shivamb/netflix-shows)
- **Columns cleaned**: `title`, `director`, `cast`, `country`, `rating`, `date_added`, `duration`, etc.
---
## 🧼 Data Cleaning Steps
✔️ Loaded the dataset using Pandas  
✔️ Renamed all column headers to lowercase and removed spaces  
✔️ Standardized text values (e.g., title-casing `country`, `director`, `cast`)  
✔️ Converted `date_added` to a consistent datetime format (dd-mm-yyyy)  
✔️ Filled missing `director` values using the mode grouped by `type` and `country`  
✔️ Dropped remaining missing values  
✔️ Removed duplicate rows  
## 🛠️ Tools Used
- Python 🐍
- Pandas 📊
- Google Colab 💻
- ----------------------------------------------------------------------------------------------------------------------------------
