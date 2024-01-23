# project-3

All code by LUCAS CHACON, RYAN DEKKER, ALENA MATUSEVICH, LILLIAN RUELAS-THOMPSON

This submission is for the Data Visualization Track and the repo contains our presentation file. As required, these data were saved to a database (MongoDB) and was uplaoded to the cloud for access. 

1) An overview of the project and its purpose

This dataset has over 9,000 records of data science positions and their salary, along with their job category, title, experience level, remote status, and company location

As we will all be on the job market in the coming months, it is important for us to learn which factors most impact salary and these data can inform us for future career path decisions. 

Here, we will treat salary as the dependent variable and explore which factors lead to either higher and lower salaries. However, the first step to finding out answers to important questions is to 'clean up' the data and remove categories that were unreliable - because the vast majority of entries were from the USA, from 2023, and employed full-time, we removed all rows that dit not fit all those criteria, which still left 6,635 entries and that sample size was large enough to infer meaningful conclusions. 


2) Instructions on how to use and interact with the project

Once the data was cleaned, it was uploaded to a database, cloud hosted by MongoDB. The Jupyter notebook code access the cloud database and access the data. We focused on a visualization on the average salary for the different job categories.  In the visualization, you can select the job category of your choice, to see the average salary in that field. You are also able to pan, box zoom, wheel zoom, refresh the data, download and/or save the visual as part of the interactivity. Our audience comes from different backgrounds, so a look at the different job categories might give insight into a field they might lean towards. 

3) At least one paragraph summarizing efforts for ethical considerations made in the project

    All of these data are anonymized and thus do not infringe on anyone’s privacy. It does not even give demographic information like age or gender. Additionally, it does not list the company name, so these data cannot be traced back to any particular group. Because all data are anonymized, we can just explore which factors most impact salary levels.   

4) References for the data source(s)

This dataset was from Kaggle - https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data

References for any code used that is not your own - Special thanks to the instructor, Brandon Knox, who helped us with the errors we were getting using the Bokeh interactive plot. 
