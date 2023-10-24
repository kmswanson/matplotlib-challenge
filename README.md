# Matplotlib Homework: Pymeceuticals, Inc.

Module 5 Challenge - Pymaceuticals

Used imports matplotlib, pandas, and scipy.stats in this challenge

Used merge with a 'how = left' to combine dataframes 

Found the unique number of mice used for this trial set of data, and then was able to extract the one
with duplicated information (g989) and was able to drop it from the data set and save the new clean dataframe
for use within the rest of the challenge.

Generated a summary statistics table using 'mean tumor volume', 'median tumor volume', 'tumor volume variance',
'tumor standard deviation', and 'tumor standard error' as the column titles.

Used both Pandas and PyPlot to produce a variety of charts to display the data in meaningful ways.
Bar charts were used to display the number of mice used for each drug regimen,using both Pandas and PyPlot.
Pandas and PyPlot were also used to make pie charts showing the distribution of male/female mice.

Quartiles, Outliers, and Boxplots were more involved. 
Calculated were the quartiles, IQR, and outliers looking for sets of the most 'promising' data.
The box plot takes these calculations and displays them in a more meaningful way that shows where the outliers are in the dataset.

The scatter plot calculates the correlation between the mouse weight and average tumor volume for the 'Capomulin' regimen.
To finish off the scatter plot data, a regression line is placed within the chart to show the 'line of best fit' or the overall trend in the data.

Multiple sources were used in making this challenge work. 
In the 'Hints and Considerations' section of the module instruction, Stack Overflow and Matplotlib documentation were both mentioned
as guidance tools. To overcome errors run into, both of these resources were used to resolve issues.
The other references for this challenge were the supplimental videos provided by the instructor within the class Slack channel, and the
#notes provided in the starter_code file, acting as a roadmap for achieving the desired results.