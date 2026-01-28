# AeroFit Treadmill Case Study

## 📌 Business Problem
AeroFit wants to understand customer purchasing behavior across different treadmill models
in order to improve marketing strategy, sales targeting, and product recommendations.

The goal is to identify **who buys which treadmill** and what factors influence that decision.

---

## 🎯 Objective
To analyze customer demographics, income, fitness level, and usage behavior and
create clear **customer profiles** for each treadmill product:
- KP281
- KP481
- KP781

---

## 📊 Dataset Overview
- Total records: 180
- Total features: 9
- No missing values
- Mix of categorical and numerical variables

### Key Features:
- Product
- Age
- Gender
- Education
- Marital Status
- Income
- Fitness Level
- Usage
- Miles

---

## 🔍 Analysis Performed
- Data understanding and validation
- Univariate analysis
- Bivariate analysis (Product vs other variables)
- Statistical summaries using `groupby` and `describe`
- Visual analysis using boxplots
- Identification of redundant variables (Usage & Miles)

---

## 📈 Key Insights
- **Income, fitness level, and usage intensity** are the strongest drivers of product choice.
- KP781 serves a **distinct premium segment** with high-income and high-fitness users.
- KP281 and KP481 cater to **mass-market and mid-tier users** with similar behavior.
- Age is **not a significant differentiator** across treadmill products.
- KP781 users show significantly higher and more consistent usage.

---

## 🧑‍🤝‍🧑 Customer Segments
- **KP281**: Entry-level users, average fitness, moderate income
- **KP481**: Regular users, slight upgrade from KP281
- **KP781**: High-income, high-fitness, performance-oriented users

---

## 🧠 Business Recommendations
- Position KP281 as a beginner-friendly, affordable treadmill
- Market KP481 as a comfort and feature upgrade
- Maintain premium pricing and performance-focused branding for KP781
- Avoid discounting KP781 heavily to preserve premium perception

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Files in Repository
- `AeroFit_TreadMill_Case_study.ipynb` – Complete analysis and code
- `AeroFit_TreadMill_Case_study.pdf` – Final report 

---

## ✅ Outcome
This project demonstrates end-to-end exploratory data analysis,
visualization, and business insight generation for customer segmentation.
