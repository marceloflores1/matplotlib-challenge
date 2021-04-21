# matplotlib-challenge
Matplotlib Homework - The Power of Plots

For this assignment we were required to analyze the data for a research study of Pymaceuticals Inc., that specializes in anti-cancer pharmaceuticals. The study has measurements for 249 mice that were identified with Squamous Cell Carcinoma (SCC). Over the course of 45 days, tumor development was measured and we were tasked to compare the performance of different drug regiments, with a specific interest in "Capomulin". 

We start with a pair of csv_files inside the "Data" folder, we import them and perform the following actions:
- Remove data with duplicate timepoints for the same MouseID. 
- Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. 
- Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen.
- Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
- Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
- Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
- Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
- Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

All of the script was performed using a Jupyter Notebook called pymaceuticals_starter.ipynb.