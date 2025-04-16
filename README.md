# 📱 Children's Screen Time Analysis Dashboard

This repository contains an interactive data analysis and visualization project focused on the **Average Daily Screen Time for Children** using real-world survey data from [Kaggle](https://www.kaggle.com/datasets/ak0212/average-daily-screen-time-for-children). The project explores key trends across **age**, **gender**, **screen time types**, and **day types** using `Plotly` in a Python notebook.

---

## 📊 Dataset Overview

The dataset includes:
- **Age**: 5 to 15 years
- **Gender**: Male, Female, Other / Prefer not to say
- **Screen Time Type**: Educational, Recreational, and Total
- **Day Type**: Weekday vs Weekend
- **Sample Size**: Number of survey respondents per category

### Notable Patterns:
- 📈 Screen time increases with age: ~1.5 hours/day at age 5 to 6+ hours/day at age 15.
- 🕹️ Recreational screen time dominates (65–80% of total).
- 📆 Weekend screen time is 20–30% higher than weekdays, especially for teenagers.
- 👦👧 Gender-based differences are present, especially in recreational time.

---

## 📂 Files in This Repo

- `Student_screentime.ipynb`: Main Jupyter Notebook with full code and visualizations
- `average-daily-screen-time.csv`: Cleaned version of the original dataset (optional to include)
- `README.md`: Project overview and usage guide

---

## 📌 Visualizations Included

✅ Total screen time trend by age (line chart)  
✅ Educational vs Recreational breakdown (pie chart)  
✅ Weekday vs Weekend comparison (grouped bar chart)  
✅ Gender-based recreational screen time (box plot)  
✅ Respondent sample size by age (bar chart)  
✅ 🔥 All charts also combined into a single interactive dashboard (via Plotly subplots)

---

## 🛠️ How to Run the Project

### 1. Clone the repo

```bash
git clone https://github.com/your-username/student-screentime-analysis.git
cd student-screentime-analysis
