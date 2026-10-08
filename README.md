# Fictional School PowerBI Dashboard
This is a PowerBI dashboard providing a snapshot of pupils' habits and performance from a fictional school's Yr 10 year group. The data it ingests is completely fictional and I made it up to be like a relational database. It contains two fact and two dimension tables. The dashboard is divided into two main analytical views:
- Student information: general and test scores:
 - Main academic/student-information dashboard
- Sports day data:
 - Focuses on exercise levels and sports day performance
Use the button at the top of each page to navigate back and forth
<img src="screenshots/Page 1.png">
<img src="screenshots/Page 2.png">

# Features
- **Subject averages**: compares average performance in the core subjects and results are grouped by combinations of major and form
  - Do students perform better in the subject they major in?
  - Performance differences between forms?
  - Which subject/form combinations achieve the highest average score?

- **Student addresses**: geographical distribution of students colour-coded by form
 - Where students live?
 - Are students from particular forms geographically clustered?
 - General geographical distribution of the Yr 10 cohort?
- **Hours spent on activity per week**: comparison of students' average weekly time spent on core subjects' study and exercise
 - Compare students' study and exercise patterns and identify unusually high or low activity levels
- **Average scores vs Study hours**: scatter plot investigating relationship between weekly study hours and average test performance for core subjects; the relationships shown are associations and should not be interpreted as causal
 - Is increased study time associated with higher marks?
 - Is the relationship stronger for some subjects than others?
 - Are there students whose results are unusually high or low relative to their study hours?
- **Sports day KPIs**:
 - **Average hours of exercise per week - cohort**: average weekly exercise level across the wider student cohort
 - **Average hours of exercise per week - sports day participants**: average weekly exercise level for students participating in sports day
  - Compare exercise habits of both groups
  - Differences between the two figures should be interpreted descriptively; they don't themselves demonstrate that Sports day participation is caused by exercise frequency
- **Number of hits vs distance of dart from centre**: distribution of number of hits and at which centre
 - visual representation of dart accuracy
 - smaller distances from the centre represent more accurate throws
- **Javelin distance and 100m run time vs exercise hours**: relationship between weekly exercise and two Sports day performance measures: average javelin distance and average 100m running time
 - Do students who exercise more throw the javelin farther?
 - Do students who exercise more complete the 100m run more quickly?
 - Error bars show variation in recorded attempts
 - Apparent relationships are correlations rather than evidence of causation

# Using the dashboard
1. Start with filters cleared to view the full population
2. Select a form or major to compare student groups
3. Use the study-hour sliders to investigate students with particular study patterns
4. Use the exercise-hours filter to investigate relationships between physical activity and other measures
5. Hover over chart points or bars where supported to view additional values
6. Use the navigation buttons to move between the pages
7. Clear filters before beginning a new comparison to avoid accidentally carrying previous selections to the next analysis

# Interpretations and limitations
This dashboard is designed for **exploratory analysis**. Users should consider the following when interpreting results:
- Correlation doesn't establish causation
- Sports day participants represent only a subset of the overall student population
- Small subgroup sizes may produce unstable averages
- Student study and exercise hours should be interpreted according to how the original data was collected
- Averages can hide variation between individual students
- Extreme values may have a noticeable effect on group averages and trend lines
- Differences between forms or majors should not automatically be interpreted as differences caused by the form or major itself
- Geographic information should be only at the level appropriate to the purpose of the analysis
