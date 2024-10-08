# Mental Health in the Tech Industry
Objective:

Performing EDA using Pandas.
Visualizing data with Matplotlib & Seaborn.
Estimating population parameters from sample data and communicating uncertainty around your insights.

Dataset:

Data for analysis used from Kaggle open source library https://www.kaggle.com/datasets/anth7310/mental-health-in-the-tech-industry/data.

Data Preparation:

SQL connection with sqlite3 library to qerry 3 data tables.
Data loading process using Pandas. 
Handling of missing values and duplicates.


Data Analysis:

Sociodemographic features(age, gender, country, race, remote work).
Prevalence of mental health disorder.
Some questions analysis by gender and having a mental health disorder at the time of survey.


Data Modification:

Updated age and gender answers from the survey. Age column had negative and high values all those were filtered after data type of SQL column was changed.
Gender answers had more than 100 unique answers, changed to 'female, 'male' and 'other'.


Half of population has a mental health disorder. Half of that do not discuss their health at work.
86% of females and 74% of males continue to have a mental health disorder at the time of the survey. Proffesional help seeks 70% of females and 55%  of males. Only half of people know about their mental health medical coverage options provided by their employeer.


1. 43% of population diagnosed with mood disorder, xnxiety disorder and Attention Deficit Hyperactivity Disorder.
2. 55% of female has a mental disorder, males - 37%.
3. Females choose not disclose illness in new jobs. 15% less females discuss their mental health in comparrison with previous co-workers.
4. 50% of males do not discuss their mental health with current co-workers.


Possible improvements:
1. Incorporating some statistical tests (e.g., Chi-square test for categorical data) would validate whether the differences observed between males and females are statistically significant or due to chance.
2. Calculate more confidence intervals.
3. Trends over the years.
4. Grouping questions by answer types, personal views, company attitude or other factors.
5. Adding plot function.
6. Investigate data design to understand target population.


Dependencies:

Required Python libraries pandas, numpy, matplotlib, seaborn, sqlite3. Requirements.txt file added.
