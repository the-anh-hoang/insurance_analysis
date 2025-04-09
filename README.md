This project explores healthcare expenditures and funding in relation to disease deaths using structured data and SQL-driven analysis within a Jupyter notebook environment.

#### 1. Required External Libraries:

pip install pandas matplotlib scikit-learn numpy  

#### 2. Project File Descriptions:

- research_question_2.ipynb: The main notebook where all analysis related to Research Question 2 is conducted. It includes data exploration, visualizations, correlation and regression analysis, and SQL queries.

- connection.ipynb: This notebook contains the code and analysis for answering Research Question 2, which investigates impactful categories in healthcare expenditures and their relationship to disease-related deaths over time.

- index.ipynb: Used to dynamically insert data into the SQLPLus database. It creates and populates tables from preprocessed CSV or dataframes.

- medicalexpenditure.sql: The SQL script that defines the schema and INSERT statements for all the medical expenditure tables used in this project.

- research_question1.ipynb: Contains the code and analysis for Research Question 1, which may focus on a different aspect of the dataset (not required for RQ2, but helpful for full understanding of the project).

- eda.ipynb: Contains early data exploration and visualization code used to understand patterns and distributions across datasets. Some charts here were helpful in shaping the later analysis.

#### 3. Location of SQL queries:

- Research question 1:

- Research question 2 (connection.ipynb): most of the cells in the file have SQL query. We only do not use SQL when it comes to visualization (line 13, 19, 21, ) and model training (line 15) 