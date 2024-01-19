# project-3

All code by LUCAS CHACON, RYAN DEKKER, ALENA MATUSEVICH, LILLIAN RUELAS-THOMPSON

An overview of the project and its purpose

This dataset has over 9,000 records of data science positions and their salary, along with their job category, title, experience level, remote status, and company location

As we will all be on the job market in the coming months, it is important for us to learn which factors most impact salary and these data can inform us for future career path decisions 

Here, we will treat salary as the dependent variable and explore which factors lead to higher and lower salaries. However, the first step to finding out answers to important questions is to 'clean up' the data and remove categories that were unreliable - because the vast majority of entries were from the USA, from 2023, and employed full-time, we removed all rows that dit not fit all those criteria, which still left 6,635 entries and that sample size was large enough to infer meaningful conclusions. 


Instructions on how to use and interact with the project

Once the data was cleaned, it was uploaded to a database, cloud hosted by MongoDB. The Jupyter notebook code access the cloud database and access the data. 

At least one paragraph summarizing efforts for ethical considerations made in the project

    All of these data are anonymized and thus do not infringe on anyone’s privacy. It does not even give demographic information like age or gender. Additionally, it does not list the company name, so these data cannot be traced back to any particular group. Because all data are anonymized, we can just explore which factors most impact salary levels.   

References for the data source(s)

This dataset was from Kaggle - https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data

References for any code used that is not your own
