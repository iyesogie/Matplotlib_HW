# Matplotlib_HW

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Instructions
Your tasks are to do the following:
Observations and Insights
* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
Summary Statistics
* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
Bar and Pie Charts
* Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
o NOTE: These plots should look identical.
* Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
o NOTE: These plots should look identical.
Quartiles, Outliers and Boxplots
* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
Line and Scatter Plots
* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Final observation
* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
1. According to the provide data, Capomulin received a higher number of data point than the other drug regimens except for one. Ramincane, had the almost the same number of data points.
2. Of the mice monitored 49.4% were female while the other 50.6% were male.
3. The data shows a decrease in the volume of the tumors in the mice treated with Capomulin over time.
