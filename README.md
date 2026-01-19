# 📊 Udemy Courses Analysis using Power BI
---
## 📌 Project Overview
---
This project focuses on analyzing Udemy course data to understand course popularity, learner behavior, and market trends using **Power BI**. 
The goal is to help instructors and stakeholders make data-driven decisions about course creation, pricing, and category selection.

The analysis covers course categories, levels, pricing models (free vs paid), subscriber engagement, and category saturation. Since course ratings were not available in the dataset, number of reviews was used as a proxy for course quality and learner engagement.

---
## 📊 Dashboard Preview

Screenshot 2026-01-19 230515.png



## 🎯 Objectives

- Identify the most popular course levels based on subscribers

- Compare free vs paid courses in terms of enrollments

- Analyze the relationship between reviews and subscribers

- Determine high ROI categories (high subscribers and engagement)

- Detect saturated categories with high competition

- Provide recommendations for instructors to maximize enrollments
---


## 📂 Dataset

**Source:** https://www.kaggle.com/datasets/andrewmvd/udemy-courses/data
**Format:** CSV
**Key columns used:**

- Course Title
- Category
- Level (**Beginner, Intermediate, Expert, All Levels**)
- Price
- Number of Subscribers
- Number of Reviews
---

## 🛠 Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power BI Service (for publishing)
- Row Level Security(Managing data based on the roles)
- GitHub (project version control)
---

## 📊 Dashboard Features

- KPI cards for total courses, subscribers, and reviews
- Category-wise and level-wise enrollment analysis
- Free vs paid course comparison
- Scatter analysis for ROI and saturation detection
- Interactive slicers for category, level, and course type
---

# 🔐 Row-Level Security (RLS)

- Row-Level Security was implemented to restrict data visibility based on user roles, simulating real-world data access control scenarios.
---

## 🔍 Key Insights

- Beginner and All-Level courses attract the highest enrollments

- Free courses generate higher overall subscribers, while paid courses show stronger average engagement

- Courses with higher reviews tend to have more subscribers

- Certain categories are saturated with many courses but low average enrollments
---

## 📌 Business Recommendations
- Focus on beginner-friendly courses to maximize reach
- Target high-demand, low-saturation categories
- Encourage learner engagement to increase reviews
- Use competitive pricing strategies
