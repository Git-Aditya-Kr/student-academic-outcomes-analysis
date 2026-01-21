# 📊 Student Performance Statistical Analysis

## 🔍 Project Overview
This project presents an applied statistical analysis examining how participation in student support programs — **AVID, SPED, ELL, and Migrant** — is associated with academic performance, measured using **grade percentage**.

The focus of the project is **statistical reasoning, inference, and interpretability**, rather than predictive machine learning. Emphasis is placed on hypothesis testing, effect size estimation, interaction analysis, and model comparison to draw responsible, data-driven insights from observational educational data.

📄 A concise project report is available:  
**Student_Performance_Statistical_Analysis_Report.pdf**

---

## 🎯 Research Questions
1. Do student support programs show statistically significant associations with academic performance?
2. Are these differences **practically meaningful**, or are they statistically significant only due to large sample size?
3. Does **migrant status interact** with grade level or class type to influence academic outcomes?

---

## 📁 Dataset Description
The dataset consists of anonymized student-level academic records.  
Each observation represents an individual student.

### Key Variables
- **gradePercentage** — Continuous measure of academic performance (target variable)
- **Program Indicators (Binary):**
  - `avid` — AVID program participation
  - `sped` — Special education status
  - `ell` — English language learner status
  - `migrant` — Migrant student status
- **Contextual Variables:**
  - `gradeLevel`
  - `classType`

---

## 🧠 Methodology
The analysis follows a structured statistical workflow:

1. Exploratory Data Analysis (EDA)
2. Distribution and assumption checks
3. Hypothesis testing (t-tests and ANOVA)
4. Linear regression modeling
5. Interaction analysis (migrant × grade level / class type)
6. Effect size estimation (Cohen’s d)
7. Model comparison using Adjusted R² and AIC

Interpretation is prioritized over computation throughout the project.

---

## 📈 Key Findings
- Student support programs exhibit **statistically significant associations** with grade percentage.
- Effect size analysis shows that most observed differences are **small in magnitude**, highlighting the importance of practical significance.
- Interaction models suggest that **migrant status modestly modifies** academic outcomes across certain grade levels and class types.
- Model comparison indicates that interaction terms add limited but meaningful explanatory value.

---

## ⚠️ Limitations
- The analysis is **observational**, not causal.
- Program participation is not randomly assigned.
- Results represent associations and should not be interpreted as policy prescriptions.
- Unobserved confounding variables may influence outcomes.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy statsmodels
