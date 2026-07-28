# From Data to Decisions: Student Performance Analytics
An end-to-end exploratory data analysis, feature engineering, and business analytics project built on the [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) dataset. This project treats a classroom dataset as a real business problem: **how should a school district allocate a limited academic-support budget to close performance gaps as efficiently as possible?** It walks from raw, unexamined data through data quality auditing, feature engineering, hypothesis-driven visual analysis, and finally to a set of prioritized, actionable recommendations.

---

## Project Overview

- **Type:** Exploratory Data Analysis (EDA) + Business Analytics
- **Dataset:** 1,000 students, 8 original columns (demographics, socio-economic proxies, test-prep status, and three exam scores)
- **Tools:** Python, Pandas, NumPy, Plotly
- **Format:** Jupyter Notebook (`.ipynb`), written in a polished, publication-ready Kaggle notebook style

## Dataset

| Column | Description |
|---|---|
| `gender` | Student's gender |
| `race/ethnicity` | Anonymized ethnic group (Group A–E) |
| `parental level of education` | Highest education level attained by a parent |
| `lunch` | `standard` or `free/reduced` — a socio-economic proxy |
| `test preparation course` | Whether the student completed a test-prep course |
| `math score` | Score out of 100 |
| `reading score` | Score out of 100 |
| `writing score` | Score out of 100 |

**Source:** [Kaggle — Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## Business Questions Answered

1. Which factors most influence student performance?
2. Does parental education affect scores?
3. Does completing a test-preparation course improve outcomes?
4. Are there gender-based performance differences, and in which subjects?
5. Which student groups are at the highest risk of poor performance?
6. Does the lunch program (socio-economic proxy) relate to performance?
7. How do the three subject scores relate to one another?
8. What does the overall distribution of performance bands look like?

## What's Inside the Notebook

1. **Project Introduction** — business context, scope, objectives, and expected outcomes
2. **Library Imports** — NumPy, Pandas, Plotly Express & Graph Objects
3. **Data Loading** — shape, dtypes, first-look inspection
4. **Comprehensive EDA** — dataset overview, descriptive statistics, and a dedicated cell-by-cell exploration of every column
5. **Data Quality Assessment** — missing values, duplicates, outliers, skewness, invalid categories
6. **Data Cleaning Recommendations** — issues explained with ready-to-run (optional, non-destructive) code
7. **Feature Engineering** — 7 new features including Total Score, Average Score, Pass/Fail, Performance Category, Score Gap, Rank, and Percentile
8. **Business Understanding** — problem framing, stakeholders, and formal hypotheses
9. **Business Questions** — the analytical questions the notebook sets out to answer
10. **Data Visualization** — 13+ interactive Plotly visualizations (histograms, box/violin plots, grouped bar charts, scatter plots with trendlines, correlation heatmap, pie chart, sunburst chart, scatter matrix), each followed by a business-insight interpretation
11. **Insights Recap** — a consolidated findings table
12. **Final Recommendations** — executive summary, business recommendations, and suggested next steps

## Key Insights

- **Test-prep completion** produces a measurable, positive score lift and is the strongest *actionable* lever in the dataset.
- **Socio-economic status** (via the `lunch` proxy) and **parental education level** both correlate strongly with performance.
- **Gender gaps are subject-specific**: female students lead in reading/writing, male students lead in math.
- **Math** is the weakest-performing, most spread-out subject and the most distinct from reading/writing.
- **At-risk students cluster** at the intersection of low socio-economic status and lack of test-prep access — a clear, targetable segment for intervention.

##  How to Run

1. Open the [Students Performance in Exams dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) on Kaggle.
2. Create a new notebook attached to this dataset.
3. Upload `students_performance_analysis.ipynb` or copy its cells in.
4. Run all cells — the dataset will already be available at `/kaggle/input/students-performance-in-exams/StudentsPerformance.csv`.

 

 
