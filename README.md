# PRODIGY_DS_02
Exploratory data analysis on the Titanic dataset: data cleaning, imputation, and visualizing how gender, class, age and fare affected survival. Prodigy Infotech Data Science Internship, Task 2.
# Task 2: Exploratory Data Analysis on the Titanic Dataset

Part of the Prodigy Infotech Data Science Internship.

## Objective
Perform EDA to explore relationships between variables and identify
patterns that influenced passenger survival.

## Dataset
Titanic dataset from Kaggle.

## Approach
- Imputed Age (median) and Embarked (mode); dropped Cabin, PassengerId
  and Ticket
- Visualized survival by gender, by class and gender, and by age
- Correlation heatmap of numeric features
- Fare vs survival box plot (log scale)

## Key findings
- Females survived at ~74% vs ~19% for males (overall ~38%)
- Survival fell by class: 1st ~63%, 2nd ~47%, 3rd ~24%
- Solo travelers and very large families had lower survival odds
- Cherbourg passengers showed higher survival, linked to more 1st-class travelers

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn
