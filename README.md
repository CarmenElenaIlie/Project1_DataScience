# Project1_DataScience

Link for GitHub Post: https://medium.com/@carmen.ilie/what-influences-your-job-satisfaction-66eaa9148042

**Description:**

This repository is for "Project: Writing a Data Scientist Blog Post" 
Using the DataSet presented below you will find a correlation between the employee Job Satisfaction and different information from the Data Set.

**Table of contents:**
- Documentation
- Lybraries
- Motivation &  Summary
- Necessary Acknowledgments

**Documentation:**
The Data Set used in order to analyse the data is gathered in "survey_results_public.csv". This file was used into the Udemy Data Science classes and it is an important database from where a lot of correlations can be performed as the number of responders are ~20000 from more than 150 countries, with different Formal Educations. Thus, the data to being analyed are ver complex and complete.

The code can be found in "Project1_DataScience.ipynb", along with their results after complilation.

**Lybraries:**
Some lybraries have been imported in order to be able to access some functions.
- pandas - used for data wrangling and data manipulation purposes
- numpy - used used to create arrays or matrices
- matplotlib.pyplot
- sklearn.model_selection - used for plotting simple 2D graphs using Python
- sklearn.linear_model - contains different functions for performing machine learning with linear models
-> sklearn.metrics - assess the quality of your predictions

**Motivation & Summary:**
In order to understand better what data may influence the Job Satisfaction given grades by ~20000 responders we needed to use predictions applyed on different columns of the Data Set. 
First of all the NaN values and cartegorical data had to be formated to fit the predictive model.
Some rows/columns containing NaN values have been dropped and the categorical values have been dummied and attached with the prefix "_" because in the .cvs the were situations when the same respondent gave more than 1 answeres to the same question.
There were used, according to the course, some methods of formating the DataSet until to get the conclusion:
- Split the DataSet into explanatory and response variables
- Split into train and test
- Instantiate
- Fit the model
- Predict using your model
- Score using your model
In the end a new function has been used by analysing the X_train DataSet and model coefficient. It's output was basically the correlation between Job Satisfaction and different columns from Data Set.
It was clearly seen that the employees with high Job Satisfaction are not interested on new opportunities and they do not even search for them. Also, the Job Search status from Stack Overflow shows that those employees are not intended into searching new jobs.
Another conclusion was that the poeple with high Job Satisfaction had reviwed very high their Career Satisfaction.

**Necessary Acknowledgments:**
Code releases under Udemy Data Science course.
