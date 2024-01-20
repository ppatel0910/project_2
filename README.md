# Spotify Streams Analysis

## We created a logistic regression model to predict the success of a song based on various metrics, such as danceability, liveliness, energy, etc. A song was considered a success if it received more than the average streams, which we calculated from our dataset. A success was denoted with a "1", otherwise it received a "0". This metric was saved into a new column "song_success". 

![classification_report_for_logistic_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/logisticregression.png)

## For the random forest classifier model, we used the cleaned data from the Logistic Regression model to fit the model. The same initial features were used, and we were able to build a successful model with a 92% accuracy rate. We were able to evaluate the importance of each feature in "X", and found that the most relevant factor in determing song success was the in_spotify_playlists data. 

![classification_report_for_the_random_tree_classifier](https://github.com/ppatel0910/project_2/blob/main/visuals/radnomtrieeclassifer.png)

![feature_importance_breakdown](https://github.com/ppatel0910/project_2/blob/main/visuals/randomtree.png)

## Linear Regression description here
![line_graph_for_linear_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/Screenshot%202024-01-20%20155528.png)

![scatter_plot_for_linear_regression_model_based_on_stream#_and_the_year](https://github.com/ppatel0910/project_2/blob/main/visuals/linearregressionscatter.png)