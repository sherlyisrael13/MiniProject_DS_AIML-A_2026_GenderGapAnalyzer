# GenderGap Analyzer: Data Analysis of Gender Wage Inequality

## Abstract
Gender wage inequality remains a significant issue across many organizations and industries worldwide. This project analyzes gender pay gap data to identify patterns of wage disparities between male and female employees. The dataset includes company-level information such as hourly pay gaps, bonus distributions, and employee representation across salary quartiles.

Using data science techniques such as data cleaning, exploratory data analysis (EDA), and data visualization, we identify key trends in wage inequality. The analysis shows that male employees are often paid higher and are more represented in top salary quartiles, while female employees are concentrated in lower pay levels. This project demonstrates how data-driven insights can help understand and address workplace inequality.

---

## Problem Statement
Gender pay inequality continues to exist across organizations, affecting fairness and workforce balance. This project aims to analyze gender pay gap data to:

- Compare salaries of male and female employees  
- Study bonus distribution differences  
- Analyze employee distribution across salary quartiles  
- Identify patterns of wage inequality using data analysis  

---

## Dataset Source

| Dataset | Source | Description |
|--------|--------|-------------|
| Gender Pay Gap Data | Public Dataset | Company-level salary and bonus data |

---

## Methodology

1. Problem Identification — Define gender wage inequality analysis  
2. Data Collection — Load dataset (paygap.csv)  
3. Data Preprocessing — Handle missing values and inspect data  
4. Exploratory Data Analysis — Analyze distributions and relationships  
5. Data Visualization — Generate graphs and charts  
6. Result Interpretation — Identify patterns and insights  

---

## Tools Used

| Tool | Purpose |
|------|--------|
| Python | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Advanced visualization |
| Jupyter Notebook | Analysis environment |
| Git & GitHub | Version control |

---

## Results

- Average gender pay gap is approximately 14%  
- Most companies show higher pay for male employees  
- Male employees dominate top salary quartiles  
- Female employees are more represented in lower salary levels  
- Bonus differences between genders are relatively small  
- Strong correlation exists between mean and median pay gaps  

---

## Team Members

| Name | Role | GitHub |
|------|------|--------|
| Josephine Sherly P | Data Analysis, Visualization | @sherlyisrael13 |
| Dhivahar B | Data Processing, Report | - |

---

## Project Workflow

### Step 1 - Data Collection
Dataset (paygap.csv) was collected and loaded for analysis.

### Step 2 - Data Preprocessing
- Checked missing values  
- Verified data types  
- Cleaned dataset  

### Step 3 - Exploratory Data Analysis (EDA)
- Analyzed salary distribution  
- Studied gender differences  
- Examined quartile representation  

### Step 4 - Data Visualization
- Pay gap distribution histogram  
- Top companies bar chart  
- Bonus comparison chart  
- Quartile distribution graph  
- Correlation heatmap  

### Step 5 - Result Interpretation
Insights were derived from visualizations to understand wage inequality patterns.

---

## Repository Structure
GenderGapAnalyzer/
├── README.md
├── requirements.txt
├── docs/
│ ├── abstract.pdf
│ ├── problem_statement.pdf
│ └── presentation.pdf
├── dataset/
│ ├── raw_data/
│ │ └── paygap.csv
│ └── processed_data/
├── notebooks/
│ └── gender_gap_analysis.ipynb
├── src/
├── outputs/
│ └── graphs/
├── report/
│ └── gender_gap_analysis.pdf


---

## How to Run

1. Clone the repository:
git clone https://github.com/sherlyisrael13/MiniProject_DS_AIML-A_2026_GenderGapAnalyzer.git
2. Install dependencies:
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook
Open:
notebooks/gender_gap_analysis.ipynb

---

## Conclusion

This project highlights the presence of gender wage inequality across organizations. The analysis shows that male employees are more likely to be in higher salary brackets, while female employees are more represented in lower pay levels. Data visualization techniques help clearly identify these disparities, supporting the need for fair compensation practices.

---

## Project Submission

This project is submitted as part of the Data Science Mini Project (2026).
