# matplotlib-challenge-

In the project, I utilized a set of pharmaceutical data to generate tables and figures regarding the comparative performace of all the drugs used in the study. First, I cleaned the data and generated summary statistics by using the 'groupby' and the 'agg' methods. 

Second, I created two bar plots using Panda's `DataFrame.plot()` method and MatPlotLib's 'pyplot' methods that show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

Next, I created two pie charts using Panda's `DataFrame.plot()` method and MatPlotLib's 'pyplot' methods that show the distribution of female and male mice in the study.

Then, I calculatd the final tumor volume of each mouse across four of the treatment regimens, and calculated the quartiles and IQR to determine if there were any potential outliers. Using Matplotlib, I generated a box plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot. 

Next, I created a line plot showing the relationship between tumor volume vs. time point for a mouse treated with Capomulin. I also generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

Finally, I calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, and plotted the linear regression model on top of the previous scatter plot.


