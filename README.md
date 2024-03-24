# Forest-Fires-in-Portugal
Description and objective: This was a data mining group project where the goal was to predict whether a forest fire in Portugal was intentional or not.

Used language: R

Project phases:
1. Data Pre-processing: This was the part I was responsible for. It consisted on data cleaning (handling missing values, correcting data) and feature engeneering (creating new variables).

2. Data Visualization: After processing the data, we have conducted exploratory data analysis to gain insights from the data.

3. Predictive Modelling: The data was splitted into 70% training and 30% testing, and we have used k-folds (10 folds) for validation. After running different models with different parameter tuning, our final model was Random Forest with a feature subset size of 4, a minimum node size of 20 and a number of trees of 100. We have obtained an AUC of around 76%.

   
Conclusion: 
One of the limitations or difficulties was making the data tidy and working in the correct formats that the models needed.
Other features and parameter tuning for different models could also be explored.
