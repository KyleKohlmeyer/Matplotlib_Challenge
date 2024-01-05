# Matplotlib_Challenge
This repository contains code that analyzes mouse tumor treatment data using Pandas Dataframes and the Matplotlib library. The code can be found in the pymaceuticals_code ipynb file, and the data studied can be found in the data folder. 
## Data cleaning
A check was performed to see if there was any mistakes in recording the data.
This consisted of looking for duplicate entries for the same mouse.
This check revealed that there was a mouse that had two different tumor volumes recorded at each timepoint
The mouse was subsequently removed from the dataset so that it did not affect the analysis
## Data Analysis
### This is just a brief summary of the analysis that was performed. Please see the code document for the complete analysis
Summary statistics were prepared for each drug treatment. The two most promising drug treatments were compared with two other treatments, and a statistical analysis was performed to find the IQR and any potential tumor volumes that were outliers. It was found that one of the drugs had a tumor volume that was a lower outlier.  Matplotlib was utilized to visualize how the two most promising drugs compared to the other treatments. Finally, a linear regression analysis was performed on the relationship between the weight of the mice and their tumor volume for the most promising drug, Capomulin. It was shown that mouse weight was directly correlated with tumor volume for mice on the Capomulin regimen.
