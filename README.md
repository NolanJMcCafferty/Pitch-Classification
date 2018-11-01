# Pitch-Classification

## Nolan McCafferty

This is a project that I completed for a job application for the New York Yankees. I built several models using the sklearn library in Python to predict the pitch type of future pitches given several variables including pitcherID, spin rate, initial x position, initial z position, x break, z break, extension, and initial speed. 

After initial exploration of the data, I implemented a simple Logistic Regression model to classify the pitches. I then tried a Random Forest model and got a very slight accuracy increase. Using the feature importances method I was able to show that the most important variables for predicting the pitch type are x break, z break, and initial speed. 
