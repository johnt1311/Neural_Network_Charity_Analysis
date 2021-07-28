# Neural_Network_Charity_Analysis
## Overview of the Analysis
Bek works for a charity is working to determine what organizations to give money to. She decides she wants to use deep learning to analyze and predict potential outcomes. She has a dataset of 34,000 organizations that would like money.
## Results
### Data Prepocessing
- The target variable is whether or not to invest.
- The features are the Status, Application Type, Affiliation, Classification, Use Case, Organization, Income Amount, Special Considerations, and Ask Ammount
- The name and EIN were removed as they were not relevant to the model
### Compiling, Training, and Evaluating the Model
- We tried a few different inputs for the model but they all had similar results. We decided that two Hidden layers were best using Relu on both.
- We never achieved greater than 75% accuracy
- We tried increasing epochs, hidden layers, and neurons to reach the desired outcome
## Summary
Given that we were not able to achieve the desired outcome, this model is probably not best to use in the real world. It could probably fit better if the number of hidden layers and activation types were adjusted.
