# Data-Science-Project1

# Data Science Salary Estimator: Project Overview 
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
## EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 

![alt text](https://github.com/Ras-hi/Data-Science-Project1/blob/main/datascience_salary_proj/salary_by_job_title.PNG "Salary by Position")
![alt text](https://github.com/Ras-hi/Data-Science-Project1/blob/main/datascience_salary_proj/positions_by_state.png"Job Opportunities by State")
![alt text](https://github.com/Ras-hi/Data-Science-Project1/blob/main/datascience_salary_proj/correlation_visual.png "Correlations")
