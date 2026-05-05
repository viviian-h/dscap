# Vivian Huang: Data Science Capstone Final Project

## Research Question:
Has time spent on educational activities varied by gender from 2003-2024? 
Are there other factors, including income, location, race or their interactions with gender that contribute to differences in time spent on education?

## Data Sources
Roster, Respondent, Activity, and Current Population Survey files from the American Time Use Survey Data (ATUS) spanning 2003-2024. Data here: https://www.bls.gov/tus/data.htm

## Sample
16,898 full-time students aged 15-24 in the ATUS dataset 

## Files:
- VivianHuang_DataScienceCapstoneFinal.pdf is the final poster
- DSCapstoneFinalProject.ipynb contains data cleaning as well as data visualization work
- DSCapstoneFinalProjectModeling.qmd contains modeling work
- The file named "Data" contains the clean data used to run the models (ds_finalproject_data.csv), predictions for the logistic regression used for plotting(pred_data.csv) and predictions for the linear regression used for plotting (pred_part2.csv) as well as zipped ATUS respondent and roster files.

## To Reproduce:
1. Run the python file (DSCapstoneFinalProject.ipynb) until *** Run R Code before this*** section
2. Use ds_finalproject_data.csv, which was created from the Python file, to run the models and create the prediction csvs.
3. Run the section after *** Run R Code before this*** to create the final graphs
