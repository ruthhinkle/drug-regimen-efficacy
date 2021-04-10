# Pymaceuticals
![Pills against pink background](https://github.com/ruthhinkle/matplotlib-challenge/blob/main/Images/pills.jpg)

## Description
This project examines various drug regimens and their efficacy at reducing tumor size in test mice. The dataset includes measurements at timepoints over the course of 45 days. In particular, it is asking how the drug Capomulin compares to the other possible treatments. 

## Observations

**Drug Regimen Efficacy**

Of the drug regimens attempted, Capomulin and Ramicane were the most likely to succeed in reducing tumor size. You can see this bear out in the "Quartiles, Outliers and Boxplots" section of this report. Ramican and Capomulin have much smaller tumor volumes at the final timepoint compared to Infubinol and Naftisol. 

**Largest Dataset: Capomulin**

As you can see in bar charts of the number of measurements for each drug regimen, Capomulin has the most measurements. Considering that Capomulin was one of the more effective drugs, this makes sense. It's possible to extrapolate the conclusion that less effective drug regimens resulted in the earlier deaths of the corresponding mice. 

**Size of Tumor and Mouse Weight Are Correlated**

If you look at the linear regression model at the bottom of this report, you can see that, for the most part, tumor size increased along with the size of the mouse. 

## Repository Contents

* Checkpoints for Jupyter Notebook
* Resources - Mouse_metadata.csv, Study_results.csv
* Jupyter Notebook Code - pymaceuticals_REH.ipynb
* Readme file