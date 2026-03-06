# 🎓 Students Mental Health EDA

An exploratory data analysis (EDA) of mental health among university students, examining the relationship between academic performance, course of study, sports engagement, study satisfaction, stress relief activities, and mental health indicators such as anxiety and depression.

---

## 📁 Dataset

Download the dataset from Kaggle: [Mental Health Survey](https://www.kaggle.com/datasets/abdullahashfaqvirk/student-mental-health-survey)

Place `MentalHealthSurvey.csv` in the same folder as the notebook before running.

The dataset contains survey responses from university students with the following features:

| Column | Description |
|--------|-------------|
| `gender` | Student's gender |
| `age` | Student's age |
| `degree_major` | Field of study |
| `cgpa` | Cumulative GPA (stored as ranges e.g. '3.0-3.5') |
| `anxiety` | Whether the student experiences anxiety (1 = Yes, 0 = No) |
| `depression` | Whether the student experiences depression (1 = Yes, 0 = No) |
| `sports_engagement` | Level of sports participation |
| `study_satisfaction` | Student's satisfaction with their studies |
| `stress_relief_activities` | Activities used to cope with stress |
| `financial_concerns` | Level of financial stress |
| `future_insecurity` | Level of concern about the future |

---

## 🔍 Key Findings

- 📈 **Higher GPA students tend to report higher anxiety levels**, suggesting high achievers may experience more academic pressure
- 🏃 **Students with moderate sports engagement have the highest average CGPA (~3.4)**, while excessive or no sports engagement is associated with lower academic performance
- 📚 **Higher study satisfaction is associated with higher CGPA**, suggesting engagement and enjoyment in academics positively influences performance
- 🙏 **Religious activities are the most common stress relief method** among students
- 💰 **Higher financial concerns and future insecurity are associated with higher depression and anxiety levels**

---

## 📊 Analysis Covered

- Univariate analysis — distribution of individual variables
- Bivariate analysis — relationships between two variables
- Multivariate analysis — pairplot across CGPA, anxiety, depression, financial concerns
- Data cleaning — converting CGPA ranges to numeric values
- Visualizations using pandas, matplotlib, and seaborn

---

## 🛠️ Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/students-mental-health-EDA.git
```

2. Download the dataset from Kaggle and place it in the repo folder

3. Install dependencies
```bash
pip install pandas matplotlib seaborn jupyter
```

4. Open the notebook
```bash
jupyter notebook students-mental-health_EDA2.ipynb
```

---

## ⚠️ Disclaimer

This analysis is for educational purposes only. Correlation does not imply causation — findings should not be interpreted as definitive conclusions about mental health.
