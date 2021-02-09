# JHSH_Project_2021
JHSH science fair project 2021. Naive Bayes AI for lung nodule cancer diagnosis.

Hi visitors! This is a project made my junior year of high school. This project was initially designed for JSHS Michigan Southeastern region.
This project takes advantage of open source data that can be accessed and used by anyone. I encourage anyone interested in AI or bioinformatics
to make use of my code, submit edits, and reach out for any assistance I can provide. As I am a novice programmer, I know there are many areas to 
streamline and improve my code. If you come across code you would like to improve, I'd be happy to update this repository with the better code.
My project relies on a dataset from GEO (Gene Expression Omnibus.) This dataset, XXX, uses microarray expression data from control subjects and 
patients with malignant lung nodules. The expression data comes from peripheral blood. From this data I was able to extract data frames using R 
and many of its modules. I saved these data sets as CSVs that I loaded into a Python Jupyter Notebook for further analysis. I strategically filtered 
and organized these data frames into a table consisting of the top 50 most differently regulated genes based on adjusted P value. I continued to use 
more Python modules to analyze the data for a Naive Bayes AI (I choose to use a 70/30 split.) After finding the most successful AI seed, I reached 
a final accuracy of just over 80%. As a diagnostic tool this is a very good efficacy. Hopefully this project can be used to improve the lives of patients
who have potential lung nodule cancer. You can find more information in both my paper and attached presentation. Thank you and have fun!
