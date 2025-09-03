# Stress Level Dataset — Task 1 (Data Cleaning).

## Objective
The goal of this task was to **clean and preprocess the raw Stress Level Dataset** so that it’s ready for further analysis or modeling.

---

## 🛠️ Steps Performed  
1. **Loaded the raw dataset** (`StressLevelDataset.csv`).  
2. **Checked for missing values** → none were found.  
3. **Removed duplicate rows** → none were present.  
4. **Standardized text columns** → converted to lowercase, removed spaces.  
5. **Fixed data types** → converted numeric/date columns where possible.  
6. **Renamed columns** → used `snake_case` (e.g., `Sleep Quality → sleep_quality`).  
7. **Saved cleaned dataset** as `StressLevelDataset_Cleaned.csv`.  

---

## 📊 Results  
- **Initial Shape:** 1100 rows × 21 columns  
- **Final Shape:** 1100 rows × 21 columns  
- **Missing Values:** 0  
- **Duplicates Removed:** 0  
- **Cleaned File:** ✅ `StressLevelDataset_Cleaned.csv`  

---

## 📂 Files in this Repository  
- 📄 `StressLevelDataset.csv` → Raw dataset  
- 🧹 `StressLevelDataset_Cleaned.csv` → Cleaned dataset  
- 📓 `data_cleaning.ipynb` → Notebook with all cleaning steps  
- 📝 `README.md` → This summary  

---

## 🚀 How to Run  
1. Install **Anaconda** (recommended) or **Python 3.10+**.  
2. Open **Jupyter Notebook**.  
3. Place all files in the same folder.  
4. Open and run `data_cleaning.ipynb`.  
5. The cleaned dataset will be saved automatically.  

---

## ✅ Conclusion  
The dataset is now **clean, consistent, and analysis-ready**.  
This task demonstrates basic **data preprocessing skills** that are essential for analytics projects.  
