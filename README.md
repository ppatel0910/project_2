# Spotify Streams Analysis

## We created a logistic regression model to predict the success of a song based on various metrics, such as danceability, liveliness, energy, etc. A song was considered a success if it received more than the average streams, which we calculated from our dataset. A success was denoted with a "1", otherwise it received a "0". This metric was saved into a new column "song_success". 

### The image below is the classification report for our initial logistic regression model. The features used in this model were danceability, valence, energy, acousticness, liveness, instrumentalness, and speechiness. The model was predicting at 70% accuracy.

![classification_report_for_logistic_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/logisticregression%20classification%20report.png)

### To improve on the models accuracy, we included more features in the model. By adding additional features, the models accuracy increased to INSERT PERCENTAGE HERE. The classification report for the second model is below. 

![classification_report_for_logistic_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/logisticregression.png)

## For the random forest classifier model, we used the cleaned data from the Logistic Regression model to fit the model. The same initial features were used, and we were able to build a successful model with a 92% accuracy rate. We were able to evaluate the importance of each feature in "X", and found that the most relevant factor in determing song success was the in_spotify_playlists data. 

![classification_report_for_the_random_tree_classifier](https://github.com/ppatel0910/project_2/blob/main/visuals/radnomtrieeclassifer.png)

![feature_importance_breakdown](https://github.com/ppatel0910/project_2/blob/main/visuals/randomtree.png)

## With the Linear Regression model we wanted to predict how the streams of songs on the Spotify platform would perform determining how old the particular song is compared to a more recent song.  Thus getting the average number of streams on the Spotify platform will provide us some of the story of how we can determine the most popular songs in a particular year will perform due to the stream count.
![line_graph_for_linear_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/Screenshot%202024-01-20%20155528.png)

![scatter_plot_for_linear_regression_model_based_on_stream#_and_the_year](https://github.com/ppatel0910/project_2/blob/main/visuals/linearregressionscatter.png)
