# 🚦 Task 4 – Traffic Accident Analysis (SkillCraft Data Science Internship)

This project is part of my Data Science Internship at **SkillCraft Technology**.

---

## 📝 Task Objective

Analyze traffic accident data to identify patterns related to:

- **Time of day**
- **Geographical areas (boroughs)**
- **Injury severity**
- **High-risk accident locations**

---

## 📁 Dataset

- **Title**: Motor Vehicle Collisions - Crashes  
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/tush32/motor-vehicle-collisions-crashes)  
- **Format**: CSV  
- **Size**: ~40 MB  
- **Rows**: 2.1+ million accident records from New York City

---

## 🔍 Columns Used

- `CRASH DATE`, `CRASH TIME`
- `BOROUGH`, `ZIP CODE`
- `LATITUDE`, `LONGITUDE`
- `ON STREET NAME`
- `NUMBER OF PERSONS INJURED`
- `NUMBER OF PERSONS KILLED`

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Key Insights & Visualizations

- **Accidents by Hour of Day**  
  → Highest between 3 PM and 6 PM (rush hour peaks)

- **Accidents by Borough**  
  → Manhattan and Brooklyn reported the highest number of collisions

- **Top 10 Most Dangerous Streets**  
  → Based on total injuries, some streets repeatedly show high incident rates

---

## 📂 Project Structure

SCT_DS_4/
├── Task_4_Accident_Analysis.ipynb # Google Colab notebook
├── Motor_Vehicle_Collisions.csv # Raw dataset (optional)
└── README.md # This file



---

## 📌 Notes

- Null values were handled by dropping rows with missing location and borough data.
- Time of accidents was extracted from the `CRASH TIME` column for temporal analysis.
- The analysis is scalable and could be extended to include weather, contributing factors, or vehicle types.

---

📈 *Task completed as part of SkillCraft Technology's Data Science Internship Program.*
