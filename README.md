# 🧠 Pokémon Data Analysis (Python + Pandas)

## 📌 Overview
This project explores a Pokémon dataset to perform exploratory data analysis (EDA) using Python.  
The goal is to understand Pokémon stats, types, and strength patterns through data cleaning and analysis.

---

## 🎯 Objectives
- Understand dataset structure and quality
- Clean and prepare raw data for analysis
- Analyze Pokémon strength, types, and generations
- Create meaningful features like Power Score
- Extract actionable insights from data

---

## 📂 Dataset
- Source: Kaggle Pokémon dataset
- Contains attributes such as:
  - HP, Attack, Defense, Speed
  - Type 1, Type 2
  - Generation
  - Legendary status

---

## ⚙️ Workflow

1. Load and inspect dataset
2. Data cleaning (missing values, duplicates, types)
3. Filtering and exploratory analysis
4. Group-based insights (Type, Generation)
5. Feature engineering (Power Score)
6. Final insights and reporting

---

## 🔍 Key Analysis Questions
- Which Pokémon is the strongest and weakest?
- Which types are most common and most powerful?
- How do Legendary Pokémon compare to others?
- Which generation has the strongest Pokémon?
- Can we classify Pokémon by strength levels?

---

## 🧪 Feature Engineering
- Power Score = Sum of all base stats
- Strength classification:
  - Weak
  - Average
  - Strong

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy

---

## 📈 Outcome
- Cleaned and structured dataset
- Multiple analytical insights derived
- Feature engineering applied
- End-to-end exploratory data analysis workflow using real dataset
- Business-style insights extracted from raw data

---

## 🚀 Future Improvements
- Add interactive visualizations
- Build dashboard (Power BI / Streamlit)
- Apply machine learning classification


## 📊 Dataset Overview (Step 1 - Load & Inspect)

- 800 Pokémon, 13 features
- No duplicate entries
- Missing values only in **Type 2** (expected — single-type Pokémon exist)
- Most common Type 1: Water
- Most common Type 2: Flying
- Legendary Pokémon: 65 (rare class ~8%)


## Step 2 - Cleaning

- 386 values missing in **Type_2**
- Missing values are represented as NaN(Maybe)
- No duplicates
- No incorrect data types
- And changed some columns name