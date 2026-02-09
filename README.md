⭐ Cycling Performance Analysis using Statistical Modeling & Linear Mixed-Effects Models
📌 Project Overview

This project presents an in-depth statistical analysis of professional cycling performance data to understand how rider classifications and stage characteristics influence performance outcomes. Using Python-based statistical techniques, the study evaluates whether observed differences in rider performance are statistically significant and whether individual rider effects contribute meaningfully beyond group-level trends.

The analysis combines classical hypothesis testing with a Linear Mixed-Effects Model (LMM) to account for repeated measurements of riders across multiple stages—an approach commonly used in applied statistics and sports analytics research.

🎯 Objectives

Analyze performance differences across rider classes (All-Rounder, Climber, Sprinter, Unclassed)

Test statistical assumptions such as normality and homogeneity of variance

Compare rider class performance using both parametric and non-parametric tests

Quantify individual rider variability using a Linear Mixed-Effects Model

Perform residual diagnostics to validate model assumptions

🧠 Methodology

Exploratory Data Analysis (EDA): Descriptive statistics and visualizations to understand data structure and distributions

Statistical Assumption Checks: Shapiro–Wilk tests for normality and Levene’s test for variance homogeneity

Hypothesis Testing: One-way ANOVA and Kruskal–Wallis tests

Post-hoc Analysis: Tukey HSD pairwise comparisons

Advanced Modeling: Linear Mixed-Effects Model with rider-level random effects

Model Validation: Residual diagnostics and intra-class correlation analysis

🛠️ Tools & Technologies

Python

Pandas & NumPy

SciPy

Statsmodels

Matplotlib & Seaborn

Jupyter Notebook

📊 Key Insights

Rider classification has a statistically significant impact on performance points

Unclassed riders demonstrate higher average performance compared to Sprinters and Climbers

Mixed-effects modeling reveals substantial rider-specific variability, justifying the use of hierarchical modeling

Residual diagnostics confirm the robustness of the fitted model
