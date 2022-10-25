# Neural Network Charity Analysis

## Overview
### Background
An investment company wants to create a neural network model that helps predict the success of funded companies.

### Purpose
The purpose of this analysis is to create a binary classifier that can predict which applicants will be successful when funded by the investment company. 

## Results
- Data Preprocessing
    - The target of the model is the "IS_SUCCESSFUL" column that determines if the investment was successful or not.
    - The features of the model are all other columns except the "IS_SUCCESSFUL" column. 
    - The variables that are neither target nor feature are the "EIN" and "NAME" columns which need to be dropped as they have no influence on the success of the investment.

- Compiling, Training, and Evaluating the Model
    - The original number of neurons in the model is 8 neurons in the first hidden layer, and 5 neurons in the second layer. I then made the model with two hidden layers with 10 neurons each. Then, I tried three hidden layers with 8 neurons in each layer. Finally, I made a model with two hidden layers of 8 and 5 neurons and changed the number of epochs to 500. 
    - I was unable to achieve an accuracy over 75% for any of the models. 
    - I attempted to increase model performance by changing the number of neurons in the model and increasing epochs. 


## Summary
Overall, the best result we were able to obtain was an accuracy of 72.7%. A different model with more hidden layers and neurons may be able to get a better accuracy.
