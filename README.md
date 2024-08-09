# Project Overview
This project explores the mental health effects of studying in a different country, using data from a Japanese international university's survey conducted in 2018. The study focuses on comparing international and domestic students, examining how factors such as social connectedness and acculturative stress impact depression levels.

# Contents of the Project
students.csv: This CSV file contains the survey data with various attributes related to students' demographics, language proficiencies, and mental health indicators.

mentalhealth.jpg: An image used in the Jupyter notebook as an illustration related to mental health.

notebook.ipynb: A Jupyter notebook that contains the analysis and SQL queries to explore the dataset.

# Data Description
The dataset students.csv includes the following key columns:

inter_dom: Type of student (International or Domestic).
region: Geographic region.
gender: Gender of the student.
academic: Academic level (e.g., Undergraduate, Graduate).
age: Age of the student.
stay: Length of stay in the current location (in years).
japanese, english: Scores representing proficiency in Japanese and English languages.
todep: Total score of depression (PHQ-9 test).
tosc: Total score of social connectedness (SCS test).
toas: Total score of acculturative stress (ASISS test).
partner, friends, parents, etc.: Data related to relationships and social support.

# Instructions for Use
Prerequisites:

Ensure you have Jupyter Notebook installed in your Python environment.
Install any required packages (e.g., pandas) using pip install pandas.
Running the Notebook:

Open notebook.ipynb in Jupyter Notebook.
Execute the cells sequentially to explore the data and run SQL queries.
The notebook starts with some markdown cells that provide context and data descriptions.
The SQL queries included in the notebook help you analyze the relationship between the length of stay and mental health indicators among international students.

# Understanding the Analysis:
The primary focus is on understanding how the length of stay (stay) impacts mental health scores (todep, tosc, toas) for international students.
The queries are structured to group the data by the length of stay and calculate the average scores for the mental health indicators.
Objective of the Analysis
The goal of this analysis is to verify whether international students experience higher risks of mental health difficulties, particularly in relation to their length of stay and social connectedness. By running the provided SQL queries, you can determine if the length of stay significantly impacts the depression scores and other mental health indicators.
