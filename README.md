# Online-Courses-Analysis-Dashboard-Power-BI-
This project presents an end-to-end data analysis of an EdTech platform using Power BI. The goal is to extract meaningful insights from online course data to help in decision-making related to course demand, instructor performance, and user engagement.

The dataset consists of multiple attributes such as course categories, skills, instructors, subtitles, and viewership metrics.

#### 🎯 Objectives
Identify most popular course categories
Analyze in-demand skills
Evaluate top instructors based on ratings
Understand impact of subtitles on engagement
Explore viewership trends based on lecture duration

#### 🛠️ Tools & Technologies
Power BI
Power Query (M Language)
DAX (Data Analysis Expressions)
Data Preparation

Performed data cleaning and transformation using Power Query:

Removed null and irrelevant values
Split multi-value columns (skills, instructors, subtitles)
Created custom columns for:
Skills count
Language count

#### 📈 Key Features & Visualizations
1. Course Popularity
Compared course types (Courses, Specializations, etc.)
Identified most consumed formats
2. Category Analysis
Ranked categories using average views
Highlighted top-performing domains like Data Science & IT
3. Skills Demand (Word Cloud)
Visual representation of most demanded skills
Key skills: Python, Machine Learning, Communication
4. Language Distribution
Majority of courses available in English
Minimal representation of other languages
5. Subtitles vs Viewership
Analyzed how subtitle availability impacts engagement
Found positive correlation with higher subtitle counts
6. Instructor Analysis
Used RANKX to rank instructors
Identified top instructors based on ratings
7. Lecture Duration vs Views
Found optimal duration range for maximum engagement

#### ⚡ Advanced Features
- Dynamic Slicers for filtering data
- Drill-down functionality for deeper insights
- Conditional DAX Measures (showing values only for top categories)
- Interactive dashboard design
