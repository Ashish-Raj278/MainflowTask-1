# MainflowTask-1
The objective given to me was :
 Analyze a dataset of student exam scores and answer specific questions, presenting findings
 using Python libraries and techniques for data analysis.


 
 The Dataset was contained in 2 csv files,For better efficiency and readability ,both the code and the attachment to view the said dataset is in Excel Wordbook form saved as a .xlsx file.


In the Data visualization part of the task,i've attached 2 png files of the student analysis graphs since jupyter notebook does not directly have that feature available to have the graphs in the Jupyter Cell itself.


In the Data Visualization part of the task,specifically question e2 ( Create a scatter plot between study time (study time) and final grade (G3))

We've got the corelation as 0.10 and 0.25 respectively for the 2 dataset, the interpretation of the numbers are:



The correlation coefficient of 0.10 and 0.25 came from the Pearson correlation calculation between the studytime and g3 columns. Let's break down what this means:

The calculation process:

First, we cleaned the data by removing quotes and converting to numeric values
Then used pandas' built-in corr() function which calculates the Pearson correlation coefficient
The formula used is: correlation = covariance(X,Y) / (std(X) * std(Y))


Interpreting the 0.10 and 0.25 correlation:

A correlation of 0.10 indicates a very weak positive correlation
The scale goes from -1 to +1, where:

0.0 to 0.1 = Negligible correlation
0.1 to 0.3 = Weak correlation
0.3 to 0.5 = Moderate correlation
0.5 to 1.0 = Strong correlation.

