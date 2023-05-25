# deep-learning-challenge



## Overview of the Analysis

The purpose of the analyis is to create a model that helps select the applicants for funding with the best chance of success in their ventures. The date is a CSV file with over 34,000 organizations that have received funding, the releveant columns include CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME AMOUNT, ASK AMOUNT, and if It was successful.


## Results

Data Preprocessing

What variable(s) are the target(s) for your model?
    *The target variable is the "IS_SUCCESSFUL" column that determines if the company was successful.
What variable(s) are the features for your model?
    * The variables that are the features are ask amount, income amount, use case,classification, affiliation, and affiliation type.
What variable(s) should be removed from the input data because they are neither targets nor features?
    *"EIN","NAME", "SPECIAL_CONSIDERATIONS", "ORGANIZATION", "STATUS", "AFFILIATION", "INCOME_AMT"
    
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
    No, I was not able to get the target model performance.
What steps did you take in your attempts to increase model performance?
    In my attempts I removed certain columns such as affiliation and Status, I tried increasing the epochs as well as the number of units in the layer, I also tried increasing the cut off for which I binned the non numerical data.

## Summary


    The model could not get above 62% with a 61.55% accuracy, enhancements to this data set that may be help increase accuracy is more features to feed the model and maybe a larger dataset.

