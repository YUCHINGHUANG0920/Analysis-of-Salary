## Analysis of Salary of "Data Engineer" and "Software Engineer"
### Overview
In this project, our objective is to unravel patterns within a dataset sourced from Kaggle, focusing on salary information related to specific job titles.

First, we use the Kaggle API to download the salary dataset. The steps involve installing the Kaggle package using "pip install kaggle," creating a file named "kaggle.json" which contains specific user credentials, creating a directory, and moving the "kaggle.json" file into this directory. Finally, adjusting the file permissions allows us to download the required salary dataset from the Kaggle website.

Next, we utilize the read_csv function from the Pandas library to read in the dataset for subsequent analysis.

For our analysis, we focus on the job titles of data engineers and software engineers. Following four analytical steps, we gain insights into the salary conditions of data engineers and software engineers in different countries and understand the factors influencing their salary. These four steps are:

1. Data Cleaning: Conducting essential data cleaning procedures.
2. Statistical Analysis: Exploring relationships among various attributes of data engineers and software engineers through statistical methods.
3. Visualization: Creating visual representations, such as charts and graphs, to identify distribution trends and explore potential factors influencing salary.
4. Export Clean Data to a Database: Transferring the cleaned data to a database for storage and further analysis.

By following these steps, we can gain a comprehensive understanding of the salary landscape for engineers across various countries and the key factors influencing their compensation.
