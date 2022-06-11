# Reducing-Commercial-Aviation-Fatalities-with-Machine-Learning-XGBoost-
This is a machine learning project on a [Kaggle](https://www.kaggle.com/c/reducing-commercial-aviation-fatalities) dataset. The training data has over 4 million rows and 28 columns. The test data has close to 18 million rows and 28 columns. 

The goal of this project is to create the most accurate model which can predict the distractive state of a commercial airline pilot based on physiological data. The model would be trained, validated and tested on physiological data collected from commercial pilots in a non-simulator environment. The data includes parameters such as EEG zones, respiration rate and galvanic skin response. 

After initial exploratory data analysis is done, classification models are built to classify each measurement into one of four states of attention. Logistic regression, decision tree classifier, random forest classifier and XGBoost Classifier algorithms were applied and their corresponding hyperparameters were tuned to get a good balance between training, validation and test log loss.

Ultimately, an XGBoost Classifier model with a specific set of tuned hyperparameters gave the lowest log loss, placing me within the top 25% of the kaggle leaderboard for this project.
