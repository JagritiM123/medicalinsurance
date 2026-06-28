**Medical Insurance Regression Model**
This model delivers how charges (insurance fee) for individuals have been impacted by their age, if the person is smoker or not and even their BMI which all over depicts how much each individual contributes.

**Notes**
* there are 6 columns and over 1300 datapoints that i have split into train and test data (by 70/30 ratio)
* core data validations and filtering is done before starting the proper analysis.
* for the columns that potentially affect the results of "charges" column are edited (justified in the code)
* all datapoints are unique, no empty strings
**_________________________________________________________________________________________**
**Tasks**
* while doing a thorough analysis, the histogram(normal plot) for charges versus the count of individuals comes out to be left skewed (Not Normalized)
* The datapoints are centralized by applying the log function in order to correctly train the model
* ensured that the model is trained with the correct "charges" value (by giving antilog)
* calculated the proportion of each affecting parameter(age,bmi,smoker) and plotted using a pie chart
* applied some edits to categorical columns (age,bmi,smoker,sex,charges,children,region) to numerical valued columns for the one's needed for the model training and testing.
* done the feature scaling using the Z-score normalization.
* provided a scatter plot for charges_log column versus age, bmi and smoker_yes (person smokes) inorder to check the spread of individual and how sparsed it is.
