# CapstoneProject : Car Insurance Claim Prediction

Phase 2 : Deliverables

## Main points from data exploaration
- View Python File: [Data Exploration Report](data_exploration.ipynb) </br>
- There are 58592 rows and 44 columns 
- The target column “Is_Claim” has 54844 zeros (0) and 3748 ones (1) 
- The data contains no null values
- Data types: 
-  float64(4), int64(12), object(28)
- Correlation:
- the correlation between the target column “Is_Claim” and the other features is low. 
- The columns with the highest correlations are policy_tenure, age_of_car, age_of_policyholder and population_density


- Tableau Dashboard:  https://public.tableau.com/app/profile/akanksha.lamba/viz/Insurancedatastatistics/DASHBOAR

Dashboard includes the following visualizations:

- Summary table: 
	- Total claims count
	- Claims based on Transmission type of the vehicle
	- Claims based on Model of vehicle
- Treemap to visualize claims based on the area cluster
- Claims based on age of the policyholder stacked bar chart will be utilized
- Claims based on various vehicle classifiers using highlight table
- Safety rating of the vehicle visualized using horizontal bar chart
- Pie-charts visualizing claims based on the cylinder type

## Machine learning model and results

Decision Tree Regressor: 



