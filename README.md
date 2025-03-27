
# 📚 Personalized Learning Dataset Analysis

Welcome to the **Personalized Learning Dataset Analysis Project**! This project explores a synthetic dataset representing student engagement, learning styles, and performance outcomes to gain insights and predict dropout risks.

---

## 📂 Dataset Overview

- **Records**: 10,000 students  
- **Fields**: 15 columns  
- **File**: `personalized_learning_dataset.csv`

### 📋 Key Features

| Column                      | Description                                       |
|-----------------------------|---------------------------------------------------|
| Student_ID                  | Unique identifier for each student               |
| Age                         | Age of the student                               |
| Gender                      | Gender (Male/Female/Other)                       |
| Education_Level             | High School / Undergraduate / Postgraduate       |
| Course_Name                 | Course enrolled (e.g., Data Science, ML)         |
| Time_Spent_on_Videos        | Time spent on videos (minutes)                   |
| Quiz_Attempts               | Number of quiz attempts                          |
| Quiz_Scores                 | Average quiz score (%)                           |
| Forum_Participation         | Number of forum participations                   |
| Assignment_Completion_Rate  | Assignment completion percentage (%)             |
| Engagement_Level            | Low / Medium / High                              |
| Final_Exam_Score            | Final exam score (%)                             |
| Learning_Style              | Visual / Auditory / Reading/Writing / Kinesthetic |
| Feedback_Score              | Student feedback (1 to 5 scale)                  |
| Dropout_Likelihood          | Yes / No (Likely to drop out)                    |

---

## 🎯 Objectives

- Explore the relationship between learning behaviors and student success.
- Identify factors contributing to dropout likelihood.
- Provide actionable insights for personalized learning programs.

---

## 🔎 Key Insights

- **Gender Distribution**: Female (48.9%), Male (47%), Other (4.1%)  
- **Education Level**: Undergraduate (50.7%) leads in enrollment  
- **Learning Styles**: Reading/Writing (25.5%), Visual (25.2%), Auditory (24.8%), Kinesthetic (24.4%)  
- **Engagement Levels**: Medium (49.3%), High (29.8%), Low (20.9%)  
- **Dropout Likelihood**: 19.6% of students are likely to drop out  
- **Performance**: Average Final Exam Score is 64.7%, with higher dropout rates linked to low assignment completion and low engagement  
- **Top Courses**: Machine Learning (20.4%), Cybersecurity (20.3%), Python Basics (19.9%)

---

## 📈 Visualizations (Power BI Dashboard)

### KPI Cards:
- Total Students
- Dropout Students
- Dropout Rate (%)
- Average Final Exam Score

### Charts:
- Bar Chart: Dropout by Education Level
- Donut Chart: Learning Styles Distribution
- Line Chart: Age vs Final Exam Score
- Scatter Plot: Quiz Attempts vs Final Exam Score (Bubble Size = Assignment Completion Rate)

### Filters (Slicers):
- Gender
- Engagement Level
- Course Name
- Learning Style

---

## 🛠️ Tools Used

- **Power BI Desktop** – For dashboard creation  
- **DAX** – To build KPIs and calculated measures  
- **Python (Pandas)** – For optional data exploration and preprocessing

---

## 🚀 How to Use This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/daveotewa/student_learning_insights.git
