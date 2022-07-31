# Neural_Network_Charity_Analysis

## Overview 
The purpose of this analysis is to create a deep learning neural network in order to classify and predict whether organizations will be successful if funded by charity organization AlphabetSoup. Over 34,000 organizations were analyzed to determine the success of the charitable donations from AlphabetSoup charity to the organization.

## Results 
#### Data Preprocessing
     - What variable(s) are considered the target(s) for your model?
       - The variable IS_SUCCESSFUL is considered the target variable for the model.

     - What variable(s) are considered to be the features for your model?
       - The variables APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT are considered the features for the model.

     - What variable(s) are neither targets nor features, and should be removed from the input data?
       - The variables EIN and NAME are neither targets nor features for the model and should be removed from the input data.

#### Compiling, Training, and Evaluating the Model
     - How many neurons, layers, and activation functions did you select for your neural network model, and why?
       - I selected 2 layers, 80 neurons for the first layer, 30 neurons for the second layer, and 2 activation functions- relu and sigmoid.

     - Were you able to achieve the target model performance?
       - No, I was not able to achieve the target model performance of 75%. The highest performance I was able to accomplish was a performance of 72.59%.

     - What steps did you take to try and increase model performance?
       - Increased the number of neurons in first layer to 120.
       - Increased the number of epochs to 100.
       - Changed the activation function to tanh.

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.


