# Starbucks-Project
## Project Overview
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.
## Problem Statement
The analysis aimed at predicting how the customer will interact with the offers that Starbuck will send foloowing these steps <br> 
1- prepared - clean the 3 data sets <br> 
2- merged the profile and transaction data <br> 
3- build the model using Decision Tree Classifier, Linear regression, Random forest models <br> 
4- Accuracy score is the best metrics to measure my  models performance by finding accurate predictions among the 3 models

##
## Installation
Anaconda Distribution has most of the libraries necessary for the analysis done.
##
### Files Descriptions

	- README.md: read me file
	- Starbucks-Project

			-Starbucks_Capstone_Notebook.ipynb - This has the entire analysis.
		- \data
                    -The data is contained in three files:
                    -portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
                    -profile.json - demographic data for each customer
                    -transcript.json - records for transactions, offers received, offers viewed, and offers completed

