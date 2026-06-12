# 🧠 Pokémon Data Analysis (Python + Pandas)

## 📌 Overview
This project is my first end-to-end exploratory data analysis (EDA) using Python and Pandas.

I worked on a Pokémon dataset to understand how different attributes like stats, types, and generations relate to each other, and to practice real data analysis workflow step by step.

---

## 🎯 Objectives
- Understand and explore a real-world dataset
- Clean and prepare data for analysis
- Analyze Pokémon strength and type distribution
- Create simple engineered features for better interpretation
- Extract meaningful insights using pandas

---

## 📂 Dataset
- Source: Kaggle Pokémon dataset
- Each Pokémon has attributes like:
  - HP, Attack, Defense, Speed
  - Special Attack / Defense
  - Type 1 and Type 2
  - Generation
  - Legendary status

---

## ⚙️ Workflow

The project was done in structured steps:

1. Load and inspect dataset
2. Data cleaning and fixing missing values
3. Filtering specific Pokémon groups
4. Group-based analysis (Type, Generation, Legendary)
5. Feature engineering for better understanding of strength
6. Extracting insights from patterns

---

## 🔍 Key Questions

- Which Pokémon types are generally strongest?
- How do Legendary Pokémon compare to normal ones?
- Is there any trend across generations?
- Can Pokémon be grouped into roles like attacker or defender?

---

## 🧪 Feature Engineering

To better understand Pokémon strength, I created new features:

- **Offensive_Power** = Attack + Special Attack  
- **Defensive_Power** = Defense + Special Defense  
- **Power_Difference** = Offensive_Power − Defensive_Power  

Based on these, Pokémon were classified into:

- Attacker  
- Defender  
- Balanced  

This helped simplify raw stats into more meaningful gameplay roles.

---

## 📊 Key Insights

- Dragon-type Pokémon tend to have the highest average attack.
- Steel-type Pokémon are strongest in defense.
- Legendary Pokémon are significantly stronger than non-legendary ones on average.
- Generation 4 shows the highest average total stats, while Generation 2 is the lowest.
- There is no clear trend showing that newer generations are always stronger.
- Most Pokémon fall into the “Balanced” category based on engineered features.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy

---

## 🚀 What I Learned
- How to structure a full data analysis project
- How to clean and explore real datasets
- How to use groupby for insights
- How feature engineering helps simplify analysis
- How to think in terms of patterns, not just code

---

## 📌 Future Improvements
- Add visualizations (matplotlib / seaborn)
- Build interactive dashboard (Streamlit or Power BI)
- Try classification model to predict Pokémon role
- Add more feature engineering ideas

---

## 📈 Final Note
This is my first structured data analysis project, focused on learning and applying real-world data analysis steps rather than building a perfect solution.