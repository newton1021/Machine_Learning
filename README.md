# Machine_Learning
Machine Learning Homework - Exoplanet Exploration

The project looked at the classification of Exoplanets based on Astronomy	data collected and reported by NASA Candidate stars classified as either 

1. CONFIRMED
1. FALSE POSITIVE
1. CANDIDATE

The Candidate measurements were removed from the dataset as the true nature of these “planets”
Is unknown. 


The data was analyzed with 3 different models.
1. Using tensorflow/ Keras Sequential and all the data parameters provided
2.  Using tensorflow/ Keras Sequential and removing the error type data from set thus keeping only 8 parameters. 
3. Using sklearn SVC model and Grid Search to hyper tune the model’s parameters. 


The results were determined by evaluation the predictive powers on a test set of data that was not used as part of the training of the model. This was 33% of the data.

Model 1  had an accurate of 0.9961 on the training data and 0.9863 on the test data 
Model 2   had an accurate of 0.8722 on the training data and 0.8761 on the test data 
Model 3   had an accurate of 0.9929 on the training data. The model parameters were C :10, gamma: 0.01, kernel: rbf

