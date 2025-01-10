# Analysis of Salary of "Data Engineer" and "Software Engineer"
### Overview
This project aims to analyze salary information for "Data Engineer" and "Software Engineer" job titles using a dataset sourced from Kaggle. Through data cleaning, statistical analysis, visualization, and database storage, we explore salary patterns and the key factors influencing compensation for these roles.

### Objectives
The primary goal of this project is to analyze salary trends among engineers across different countries and identify key factors affecting compensation. By exploring the influence of age, years of work experience, and education level, this project aims to provide insights for career growth and industry benchmarks.

### Technologies and Frameworks 
- **Python**: Data processing, statistical analysis, and visualization.  
- **Libraries**: Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn.  
- **Data Source**: Kaggle dataset. 

### Features
1. **Data Cleaning**: Remove irrelevant or incomplete records.  
2. **Statistical Analysis**: Examine relationships between age, experience, education, and salary.  
3. **Visualization**: Create charts and graphs to illustrate trends and distributions.  
4. **Data Export**: Save cleaned data to a database for further analysis.  

### How to Build and Run 
1. First, we use the Kaggle API to download the salary dataset. The steps involve installing the Kaggle package using "pip install kaggle," creating a file named "kaggle.json" which contains specific user credentials, creating a directory, and moving the "kaggle.json" file into this directory. Finally, adjusting the file permissions allows us to download the required salary dataset from the Kaggle website.
2. Next, we can run the [analysis script](https://github.com/YUCHINGHUANG0920/Analysis-of-Salary/blob/master/Analysis%20of%20Salary.ipynb)

### Results
1. **Age**: A moderate correlation (0.67) between age and salary shows that older engineers tend to earn more.
2. **Years of Experience**: A strong positive correlation (0.71) highlights work experience as the most influential factor in determining salary.
3. **Education Level**: Education level impacts minimum salaries but has limited influence on maximum compensation.
4. **Key Insight**: Work experience and age significantly affect salary, while education level has a minimal impact.

### Conclusion
This analysis reveals that work experience is the strongest driver of salary growth among engineers, followed by age. Education level, while important for entry-level positions, does not strongly influence maximum earning potential.

### Future Work
Further analysis can include other variables like industry, job role, or location-specific factors to enhance insights.
