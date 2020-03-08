# Matplotlib Homework - The Power of Plots

## Background

This data examines complete data from Pymaceuticals most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

The tasked was to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


## Observations (Top level summary of study results)

* Looking across all generated figures and table here are three observations or inferences that can be made from the data. 

* Details regarding generated figures and tables are found below

All the tumor volumes at the original timepoint are equal at 45 mm3.

This allows comparison of final tumor volumes as one measure of drug efficacy. 

# Observation 1: Only two drugs reduce the average tumor volume, Capomulin is one of them. 
Inspecting the mean tumor volume at the final time point, only **two** drug regmimens **reduce** the tumor volume, _Capomulin_ and _Ramicane). 

Interestingly, both of these drugs have around 22\% (or 40) more datapoints than the other regimens as seen in the table below 

| Drug Regimen     | Number of Samples |
|------------------|-------------------|
| Capomulin        | 230               |
| Ramicane     228 | 228               |
| Ketapril     188 | 188               |
| Naftisol     186 | 186               |
| Zoniferol    182 | 182               |
| Stelasyn     181 | 181               |
| Placebo      181 | 181               |
| Infubinol    178 | 178               |
| Ceftamin     178 | 178               |
| Propriva     161 | 161               | 




## Outcomes

This notebook contains the following:

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* A bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.

  * **NOTE:** These plots look identical, just demonstate two approaches

* A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

  * **NOTE:** These plots look identical, just demonstate two approaches

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* A Matplotlib  box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. All four box plots are within the same figure. 

* Aline plot of time point versus tumor volume for a single mouse treated with Capomulin.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. A Plot the linear regression model on top of the previous scatter plot.

## Observations

* Looking across all generated figures and table here are three observations or inferences that can be made from the data. 

* Details regarding generated figures and tables are found below

### Copyright

Ann McNamara © 2020. All Rights Reserved.
