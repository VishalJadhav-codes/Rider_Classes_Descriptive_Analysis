# 🚴‍♂️ Cycling Performance Analysis using Statistical Modeling & Linear Mixed-Effects Models

## 📌 Problem
Understanding athlete performance in professional cycling is complex due to:
- 🚴 Variations in rider roles (Climber, Sprinter, etc.)
- 🏁 Different stage conditions and race dynamics  
- 🔁 Repeated measurements of the same riders across multiple stages  

Traditional analysis often fails to capture **both group-level differences and individual rider variability**.

👉 This project aims to determine:
- Whether rider classifications significantly impact performance  
- Whether individual rider effects contribute beyond overall trends  

---

## 💡 Solution
Performed an in-depth **statistical analysis and modeling** of cycling performance data using both classical and advanced techniques.

Approach:
- 📊 Conducted Exploratory Data Analysis (EDA) to understand distributions  
- 🧪 Tested statistical assumptions (normality & variance)  
- 📈 Applied hypothesis testing to compare rider classes  
- 🧠 Built a **Linear Mixed-Effects Model (LMM)** to capture rider-specific variability  
- ✅ Validated model using residual diagnostics  

---

## 🧠 Methodology

- 📊 **EDA**: Descriptive statistics & visualizations  
- 🧪 **Normality Test**: Shapiro–Wilk Test  
- ⚖️ **Variance Test**: Levene’s Test  
- 📈 **Hypothesis Testing**:  
  - One-way ANOVA (parametric)  
  - Kruskal–Wallis Test (non-parametric)  
- 🔍 **Post-hoc Analysis**: Tukey HSD  
- 🤖 **Advanced Modeling**: Linear Mixed-Effects Model (LMM)  
- ✅ **Model Validation**: Residual diagnostics & intra-class correlation  

---

## 🛠️ Tech Used
- 🐍 Python  
- 📊 Pandas, NumPy  
- 📉 Matplotlib, Seaborn  
- 📐 SciPy (Statistical Testing)  
- 🤖 Statsmodels (LMM)  
- 📓 Jupyter Notebook  

---

## 📊 Results

Key findings from the analysis:

- 📈 Rider classification has a **statistically significant impact** on performance  
- 🚴 Unclassed riders showed **higher average performance** compared to Sprinters and Climbers  
- 🧠 Linear Mixed-Effects Model revealed **strong rider-specific variability**  
- ✅ Residual diagnostics confirmed **model reliability and robustness**  

👉 Insight:
Both **group-level factors** (rider class) and **individual-level differences** significantly influence performance.

---

## 📷 Screenshots

> Add visualizations here soon

Examples:
- Distribution plots  
- Boxplots by rider class  
- Residual diagnostics plots  
- Model summary output  
