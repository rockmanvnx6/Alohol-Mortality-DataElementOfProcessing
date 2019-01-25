"""
	Name: Thang pham
	Student ID: 940814
	Folder: PHASE 3 CODE.
"""

Files:
	- PHASE 3 REPORT.pdf
	- Crashes_Last_Five_Years.csv
	- total_alcohol_consumption.csv
	- Underlying_causes_of_death.xls (Pre-processed using Excels)
	- Underlying_causes_of_death_raw.xls (Before pre-processed)
	- Draft_1.ipynb - Old Python code from stage 2
	- Draft_2.ipynb - Draft Python code for stage 3
	- MAIN.ipynb - MAIN CODE FOR STAGE 3.
--------------------------------------------------
MAIN.ipynb Structure:
	
	CELL 1. Libraries & global functions.
--------------------------------------------------
	PRE-PROCESSING & INTERGRATION

	CELL 2. Python code for Crashes_Last_Five_Years.csv; including drawing graphs,finding outliers and boxplot.
		- The two commented codes in the end is executable by uncommenting to display the outliers
		of Alcohol Fatality and Number of Crashes. However, only 1 data is allowed to display at
		a time.

	CELL 3. Lag plot for outliers.

	CELL 4. Python code for Underlying_causes_of deaths and its outliers.
		- In the code file included the detail information to see the data in each year, from 2007-2016.

	CELL 5. Parallel coordinate graph for alcohol death by causes from 2012-2016

	CELL 6. Python code for total_alcohol_consumption.csv and its outliers.
		- A for loop in the end to display the annotate of the total alcohol consumption for each year.
--------------------------------------------------
	ANALYSIS & FINDING CORRELATIONS.


	CELL 7. Normalize both datasets of crashes last 5 years fatalities and alcohol consumption
	
	CELL 8. Regression line between fatalities and alcohol consumption.
		- Pearson correlation (r) between alcohol consumption - fatality, crashes, injuries.



	CELL 9. Regression line between alcohol consumption and alcohol diseases and its Pearson correlation value.

	CELL 10. Finding the Pearson linear correlation value between each of the causes with alcohol consumption. 
		- In the data it's comparing K70 with alcohol consumption.



	CELL 11. Pie chart showing which beverage accounted for the most alcohol consumption.
		- Pearson correlation value between 3 main beverages with total alcohol, car crash fatal and disease.
	
	CELL 12. Linear correlation (normalized) between alcohol and car crash and disease together.
		=> No relation
	CELL 13. Mutual information between alcohol and car crashes + disease from 2012-2017
		=> No relation.

End of File.