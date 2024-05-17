Movie Rating Prediction Model:-
This project implements a machine learning model for predicting the ratings of movies based on various features such as genre, year, duration, and number of votes. The model utilizes the Random Forest Regressor algorithm, which is a popular ensemble learning technique capable of handling both numerical and categorical data.

Features:-
The model takes the following features as input:

Year: The release year of the movie.
Duration: The duration of the movie in minutes.
Votes: The number of votes received by the movie.
Genre: The genre(s) of the movie.
Dataset
The model is trained on a dataset containing information about movies, including the features mentioned above and the target variable, which is the movie rating.

Usage:-
To use the model:

Training: The model can be trained using the provided dataset. Run the train_model.py script to train the model and save it for future use.

Prediction: Once trained, the model can make predictions on new data. Provide the relevant features of a movie (e.g., year, duration, votes, genre) to the trained model, and it will output a predicted rating for the movie.

Evaluation:-
The performance of the model can be evaluated using metrics such as Root Mean Squared Error (RMSE) on a test dataset. This helps assess how well the model generalizes to unseen data.
