# Student Exam Performance Dashboard

This project presents an interactive Power BI dashboard built as part of a Junior BI Analyst assessment. The dashboard provides a comprehensive analysis of student exam attempts, performance trends, pass/fail outcomes, and exam-level insights.

<img width="1207" height="678" alt="Image" src="https://github.com/user-attachments/assets/12912604-4369-457e-8466-53eebaf410b8" />

# 📊 Key Features:

📅 Day-wise Exam Attendance Trend (Line Chart)

📚 Stacked Bar Chart: Daily Attempts by Exam

🏆 Top 5 Students in Each Exam using DAX-based RANKX

📈 Performance Trend Classification: Improved / Declined / Same / First Attempt

🎯 KPI Cards for Total Attempts, Average Score, Pass Rate, and Exams Taken

🔍 Slicers for dynamic filtering by Exam Name, Student ID, Attempt Date, and Performance Trend

# Key Insights:

1. Over 40% of students improved their performance on second attempts.

2. Subjects like Biology and Physics showed higher decline rates compared to English and History.

3. Score and performance trends helped identify learning gaps and curriculum improvement opportunities.

# Tools & Technologies:

* Microsoft Power BI (Data Modeling, DAX, Visualization)

* Excel (Data Source)

* Power Query (Data Cleaning and Transformation)

# Summarizing My Key Findings & Assumptions Made :

This Power BI dashboard analyzes student performance across multiple exam attempts, providing insights into exam trends, pass rates, and individual progress. The dataset includes information on student IDs, exam names, attempt dates, and result metrics (total answers, correct and incorrect responses).

# Key Findings:

# 1. Attempt Trends:

(a) Daily attendance shows consistent activity across weekdays, with peaks observed mid-week.

(b) Most students attempt exams between 10 AM and 3 PM (inferred from time column before transformation).

# 2. Pass Rate:

(a) The overall pass rate is approximately 62%, with variation across subjects.

(b) Science-based exams (e.g., Biology, Physics) had the lowest pass rates, while English and History showed stronger student outcomes.

# 3. Performance Improvement:

 Over 40% of students showed improvement in their second attempt.

# The "Performance Trend" breakdown reveals:

• Improved: 41%
• Declined: 19%
• Same: 13%
• First Attempt: 27%

# Top Performers:

(a) The ranking model (RANKX) highlighted consistent high scorers across all exams.

(b) Bar charts show the Top 5 students per exam, with scores above 85% in most cases.

# Decline Indicators:

A subset of students consistently declined after the first attempt, particularly in exams with time constraints or negative marking.

# Assumptions:

(a) The student identifier is assumed to be user_id from the exam_sessions table.

(b) Attempt date is derived from user_exam_ends_at, converted to date-only format.

(c) Pass/fail is determined based on a 50% score threshold (derived or assumed based on correct/total answers).

(d) Score = (correct answers / total answers) × 100, unless a detailed marking scheme is provided.

This dashboard enables educators and stakeholders to monitor student progress, detect knowledge gaps, and improve instructional design based on attempt behaviors.
