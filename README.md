
## Overview of the analysis: Explain the purpose of this analysis.
The features in the provided dataset will create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The model will be determined by the features in a dataset of over 34,000 organizations that have received funding from Alphabet Soup.

## What variable(s) are the target(s) for your model? 
The target variable measured whether the charitable donations were used effectively, and is stylized in the dataframe as "IS_SUCCESSFUL."
## What variable(s) are the features for your model? 
The features used in the model were application type, classification, use case, organization, status, income amount, whether or not there were special considerations, and the ask amount.
## What variable(s) should be removed from the input data because they are neither targets nor features?
Employer ID numbers and anmes were dropped from the input data.

## How many neurons, layers, and activation functions did you select for your neural network model, and why?
I selected two hidden layers and two activation functions: relu for the hidden layers and sigmoid for the output layer, in my neural network model. I used 80 nodes in the first hidden layer and 30 in the second.
## Were you able to achieve the target model performance? 
No. The highest accuracy I was able to achieve was 72% in three attempts.
## What steps did you take in your attempts to increase model performance?
In order to increase model performance, I imported the normalize function for the training and testing data. I also increased the number of epochs from 100 to 500. 
I used recommendations from the following website to achieve 75% accuracy.
https://saturncloud.io/blog/how-to-improve-accuracy-in-neural-networks-with-keras/
## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
75% accuracy is not ideal. In order to increase accuracy further, other algorithms for binary classification should be considered, such as a decision tree. 


