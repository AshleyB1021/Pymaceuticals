# Pymaceuticals Anti-Cancer Medication Study Analysis

## Overview

In this assignment, I analyzed the results of an animal study conducted by Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The study aimed to compare the effectiveness of various drug regimens, including Capomulin, in treating squamous cell carcinoma (SCC), a form of skin cancer.

## Instructions: 

### Prepare the Data

* Merge the mouse_metadata and study_results DataFrames into a single DataFrame.
* Check for duplicate mouse IDs and remove any duplicate time points.

### Generate Summary Statistics

* Create a DataFrame of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.

### Create Bar Charts and Pie Charts

* Generate bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen.
* Create pie charts showing the distribution of female versus male mice in the study.

### Calculate Quartiles, Find Outliers, and Create a Box Plot

* Calculate the final tumor volume of each mouse for the most promising treatment regimens.
* Determine potential outliers and create a box plot to visualize the distribution of final tumor volume.

### Create a Line Plot and a Scatter Plot

* Generate a line plot of tumor volume versus time point for a mouse treated with Capomulin.
* Create a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

### Calculate Correlation and Regression

* Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
* Plot the linear regression model on top of the scatter plot.

