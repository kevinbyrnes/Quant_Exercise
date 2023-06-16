ReadMe

Quant Exercise
Kevin Byrnes
6/15/2023

Overview:
This repository contains a Jupyter notebook containing the python code for cleaning the data in Quant_Exercise.csv, as well as an overview of the exploratory data analysis
that led to this data cleaning.  Also included is the source data Quant_Exercise.csv.

The goal of this Jupyter notebook is to clean the data from the source csv and to save the cleaned data to a new csv (out.csv).
In particular, we focus on detecting potentially bad data, and finding reasonable ways of imputing missing values.


To run:
Run locally (preferred method):
Download the Jupyter notebook from this github repository (note make sure you download the .ipynb file) and the supporting Quant_Exercise.csv file.
Save both files to the same local directory (this is where the notebook will search for the source data).
This notebook will then write the cleaned data to the same local directory.

Run online (not tested):
Github has a Jupyter notebook renderer.
Also highly recommended is nbviewer (https://nbviewer.org/)


Assumptions/Visualization/Other output:
Since this is a Jupyter notebook, the assumptions used are listed directly in the notebook.  
We assume no background knowledge of the dataset other than that it is PA census data.
In particular, we do not assume to know the meanings of the columns, or even whether they are sorted.  So a lot of focus is given to making reasonable
data cleaning assumptions given an unfamiliar dataset.

Instead of generating a separate output file or series of data visualizations, we will use the notebook to look directly into the data, 
and to produce visualizations as we step through the code as needed.



