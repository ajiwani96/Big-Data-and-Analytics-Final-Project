# Big-Data-and-Analytics-Final-Project
1. Abstract: 
	we have used various datasets from the city of Toronto open data repository to creates one larger data 	set consisting of count data of the number 	of resources available to the public per neighbourhood ID.
2. Data Compilation.ipynb:
	Here we take in the various datasets clean them, remove missing values, and combine them into a 	single dataset, pandas.csv
3. Data Visualisation:
	This is both by submission for Module 2 and part of my submission with Module 3. 
	Here we start exploring the data more by looking at its summary, spread, etc. using histograms, bar 	charts, scatterplots and box plots to look at its distribution and to see if any variables are associated 	with each other. 
	We begin the process of feature selection using filter methods by creating a correlation matrix of the 	variables to see if any of them are highly correlated with each other. We attempt to fit the data to a 	multiple linear regression 	model, however normality assumptions are violated.
	We transformed the response variable C_Rate from a continuous variable to a categorical 	variable.
	We constructed a Learning Vector Quantization model to estimate variable importance in our datasets 	to see if we can further reduce the dimensionality of our data using wrapper feature selection methods.
4. Crime Data Further Feature Selection and Decision Trees:
	There are two files here, both go through the same process of using decision trees to help with feature 	selection.
		one file does this for the data set where the values of the features and crime rate are taken in the 		same year.
		one does this for when values of crime rate are taken three years after values of features.
	For each data set we create small decision trees to help us see what our most “important” variables 	are. 
	We also implement permutation feature importance to further evaluate the importance of our features. 	We try to add and remove features from our models     to see if it will further improve model performance 	(forward/backward selection)
5. EDA, Data Visualisation, Features Selection, Decision Trees:
	A pdf compilation of the data visualisation and crime data further feature selection files
