# 📊 International Student Mental Health Analysis

🎯 Project Objective
This project explores a dataset from a Japanese international university to analyze the relationship between an international student's length of stay (stay) and their mental health diagnostic scores. Specifically, it examines scores for:

PHQ-9 (todep): Depression severity.

SCS (tosc): Social connectedness.

ASISS (toas): Acculturative stress (stress from adapting to a new culture).

🛠️ Technical Skills Used
SQL (PostgreSQL): Utilized advanced querying techniques including:

GROUP BY for data aggregation.

WHERE clauses to filter for international students (inter_dom = 'Inter').

ROUND() and AVG() functions for statistical cleaning.

ORDER BY for logical data presentation.

Data Analysis: Interpreting trends across different durations of stay.

📈 Key Findings
Based on the analysis of 201 international students:

Acculturative Stress Peaks: Students staying for 4 years reported the highest average acculturative stress (87.71).

Social Connection: Social connectedness scores remained relatively stable across the first few years (averaging ~37-38) but showed significant variation in long-term residents.

Sample Trends: The majority of the student population in this study had a stay duration of 1 to 3 years.

🗄️ Dataset
The data is sourced from students.csv, which includes both domestic and international student records. The analysis focuses strictly on the international segment to identify unique challenges faced by students studying abroad.
