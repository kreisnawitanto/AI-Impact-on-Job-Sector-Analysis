# AI Adoption and Workforce Productivity Analysis

## 1. Project Background

### 1.1 Business Context

Artificial Intelligence (AI) is increasingly being adopted across industries to improve operational efficiency, automate repetitive tasks, and support decision-making. However, organizations still need to understand whether higher AI adoption actually improves employee productivity and work performance.

This project analyzes workforce data to evaluate AI adoption across industries and job roles while investigating its relationship with productivity, work efficiency, and job satisfaction. The findings are intended to support organizations in making evidence-based decisions regarding AI implementation strategies.

---

### 1.2 Business Questions

This analysis aims to answer the following questions:

1. How is AI adoption distributed across different industries?
2. How is AI adoption distributed across different job roles?
3. Does AI adoption significantly influence employee productivity?
4. Does AI adoption affect job satisfaction?
5. Does AI adoption improve work efficiency?
6. What insights can organizations use when planning AI implementation?

---

## 2. Data Preparation & Data Structure

### 2.1 Dataset Information

Source : Kaggle – AI Impact on Job Sector

Dataset Characteristics:

- 2,000 Records
- 20 Variables
- CSV Format

The dataset contains employee demographic information, AI adoption levels, salary information, work performance metrics, productivity changes, job satisfaction, and work efficiency scores.

---

### 2.2 Data Cleaning & Preparation

Several preprocessing steps were performed before conducting statistical analysis:

- Converted raw CSV into Excel Table
- Split combined text using Text to Columns
- Standardized categorical values
- Validated numerical variables
- Recalculated Salary Change (%)
- Verified Experience Group classifications
- Checked missing values
- Ensured consistency across related variables

---

### 2.3 Data Quality Assessment

Data quality validation confirmed that the dataset is suitable for analysis.

Assessment includes:

- Missing Values ✔
- Duplicate Records ✔
- Data Types ✔
- Category Consistency ✔
- Numerical Validation ✔
- Logical Consistency ✔ 

---

### 2.4 Tools Used

- Microsoft Excel
- Python (EDA & Statistical Analysis)
- Power BI

---

## 3. Executive Summary

The analysis reveals that AI adoption is relatively balanced across industries, although adoption levels vary considerably by job role. Statistical analysis indicates that higher AI adoption is associated with significantly greater employee productivity and work efficiency.

However, AI adoption does not show a statistically significant relationship with employee job satisfaction. These findings suggest that while AI can improve operational performance, organizations should complement AI implementation with initiatives focused on employee experience and engagement.

---

# 4. Deep Analysis

## 4.1 AI Adoption Across Industries

Healthcare records the highest proportion of High AI Adoption (41.85%), while the IT industry has the largest percentage of Low AI Adoption (35.57%). Manufacturing is primarily characterized by Medium AI Adoption (37.29%).

Overall, AI adoption is relatively balanced across industries, with no industry exceeding 50% in any adoption category.

---

## 4.2 AI Adoption Across Job Roles

AI adoption differs substantially across occupations.

Key findings include:

- Doctors have the highest High AI Adoption (47.06%)
- Teachers follow with 45.00%
- Sales Associates reach 42.50%
- Auditors show the highest Low AI Adoption (42.42%)
- Professors have the highest Medium AI Adoption (42.86%)

These differences indicate that AI implementation depends heavily on job characteristics and work requirements.

---

## 4.3 AI Adoption and Employee Productivity

One-Way ANOVA was conducted to evaluate productivity differences among AI adoption groups.

Results:

- F Statistic = 4.978
- p-value = 0.007

Because p < 0.05, the null hypothesis was rejected.

Employees with High AI Adoption achieved the highest average productivity improvement (10.96%), indicating that greater AI adoption is associated with increased productivity.

---

## 4.4 AI Adoption and Job Satisfaction

Average job satisfaction remains relatively similar across all AI adoption levels:

- Low = 6.05
- Medium = 5.99
- High = 6.03

ANOVA results (F = 0.1571, p = 0.8547) indicate no statistically significant difference in employee job satisfaction among AI adoption groups.

---

## 4.5 AI Adoption and Work Efficiency

Average work efficiency increases alongside AI adoption.

Average Work Efficiency Score:

- Low = 0.63
- Medium = 0.68
- High = 0.71

ANOVA confirms the difference is statistically significant:

- F = 5.5839
- p = 0.0038

These results suggest a positive relationship between AI adoption and employee work efficiency.

---

# 5. Recommendations

## Recommendation 1 — Expand AI Adoption in Productivity-Oriented Functions

**Finding**

Higher AI adoption is associated with significantly greater employee productivity.

**Recommendation**

Organizations should prioritize AI implementation in departments where productivity improvements can generate measurable business value.

**Expected Impact**

- Higher operational productivity
- Faster task completion
- Better resource utilization

---

## Recommendation 2 — Increase AI Utilization to Improve Work Efficiency

**Finding**

Employees with High AI Adoption achieve the highest work efficiency scores.

**Recommendation**

Provide AI-based tools and workflow automation for repetitive operational activities.

**Expected Impact**

- Reduced manual workload
- Improved operational efficiency
- More consistent work performance

---

## Recommendation 3 — Support AI Adoption with Employee Development

**Finding**

Job satisfaction does not significantly change despite increased AI adoption.

**Recommendation**

Complement AI implementation with employee training, communication, and change management programs.

**Expected Impact**

- Higher employee acceptance
- Better adoption success
- Improved organizational readiness

---

## Recommendation 4 — Develop Industry-Specific AI Strategies

**Finding**

AI adoption varies considerably across industries and occupations.

**Recommendation**

Customize AI implementation based on operational needs rather than applying a single strategy across all business functions.

**Expected Impact**

- Better AI investment decisions
- Higher implementation effectiveness
- Improved business outcomes

---

## Dashboard Preview

### Overview Dashboard

- AI Adoption Distribution
- Productivity Analysis
- Job Satisfaction
- Work Efficiency
- Industry Comparison
- Job Role Comparison


---

## Tools

- Microsoft Excel
- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - SciPy
- Power BI

---

## Dataset

- Source: Kaggle
- Dataset: AI Impact on Job Sector
- Records: 2,000
- Variables: 20 

---

## Author

**Kreisna Witanto**

Information Systems Graduate

Data Analytics | Excel | Python | SQL | Power BI
