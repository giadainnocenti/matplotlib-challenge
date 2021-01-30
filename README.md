# matplotlib-challenge

This data analysis was done on a trial study for SCC tumor treatment on 249 mouses. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of the drug of interest, Capomulin, versus the other treatment regimens. The executive team wants all the tables and figures needed for the technical report of the study along with a top level summary.

The study raw data are reported in data[./data]. The [script](./pymaceuticals_starter.ipybn) relies on the followeing Python libraries: [matplotlib](https://matplotlib.org/), [pandas](https://pandas.pydata.org/docs/), [scipy](https://docs.scipy.org/doc/scipy/reference/) and [numpy](https://numpy.org/doc/). 

The main observations are reported at the top of the notebook and here for your convenience:
1. Capomulin and Ramicane showed the best performances out of the 10 drugs tested as suggested by the smallest mean tumor volume.
2. Capomulin and Ramicane have an higher number of measurements with respect to all the other drugs, probably because of the promising results. In fact, at 45 days of observation their performances seems comparable.
3. Apparently, The heavier is the mouse the larger is the average tumor volume. In my opinion, although the correlation between these two factors is good (pearson correlation = 0.84) this is not a conclusive evidence. In fact the drug efficiency may be the same in the lighter and heavier mouses. Further investigation are necessary before claiming this observation as conclusive. .

* The data have been checked for duplication and if any duplicate subject found was removed from the analysis.
* The summary statitic (mean, median, variance, standard deviation, and SEM) of the tumor volume was evaluated for each drug. The number of total measurements for each drug was reported in a bar plot while the gender percentage of the mouses was plotted as a pie chart (The study was well balanced in terms of gender). 
* The executive team wanted a break down of the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. A boxplot was made to compare performance and highlight eventual outliers.
* The mouse y793 which showed the maximum total tumor volume at 45 days was chosen to generate a line plot of tumor volume vs. time point for Capomulin.

* Finally, a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen was generated and the correlation coefficient was evaluated. Additionally, the linear regression model between mouse weight and average tumor volume for the Capomulin treatmentwas plotted on top of the previous scatter plot.


### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
