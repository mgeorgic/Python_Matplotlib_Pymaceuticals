# Python_Matplotlib_Pymaceuticals

This was a homework assignment for DU's Data Bootcamp.

Using a dataset from faux Pymaceuticals Inc, I analyzed the data concerning mice and their reactions to certain anti- cancer pharmaceuticals. Potential drug regimes were used on 248 mice, with almost even gender counts, to test for the presence of squamous cell carcinoma (SCC), or type of skin cancer, and analyze the treatment results. The specific drug of choice was, Capomulin, but the other's included in the study were: Ramicane, Ketapril, Naftisol, Zoniferol, Stelasyn, Placebo, Infubinol, Ceftamin, and Propriva.

Navigation:
- You can view all the graphs created by looking in the 'Images' folder
- Code is located in the 'HW_Code.ipymb'
- The original documentation and intructions for the Homework is in the 'Instruction and Grading' folder
- The original datasets are located in the 'Resources' folder

What I performed on the data:
- Removed any Mouse ID data cointaining duplicate time points.
- Used the cleaned data for the remaining steps.
- Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's PyPlot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
- Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
- Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Used Matplotlib to generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
- Selected mouse 'm601' with a Capomulin regime and generated a line plot of tumor volume vs. time point for the data.
- Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
- Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 
- Plotted the linear regression model on top of the previous scatter plot.
