# The Power of Plots


![Laboratory](Images/Laboratory.jpg)


In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The project was tasked to generate all of the tables and figures needed for the technical report of the study and also a top-level summary of the study results.

## Data Cleaning 

* Checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.


## Analysis

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.


![Treatments](Images/treatments.png)


* Generated a pie plot used both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.


![Pieplot](Images/Pie.png)


* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Used Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![Capomulin](Images/capomulin.png)



![Ramicane](Images/ramicane.png)



![Infubinol](Images/infubinol.png)



![Ceftamin](Images/ceftamin.png)



* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.



![TumorTime](Images/tumor_time.png)



* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.



![CorrelationScaatter](Images/correlation_scatter.png)




- - -

## References

Mockaroo, LLC. (2021). Realistic Data Generator. [https://www.mockaroo.com/](https://www.mockaroo.com/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
