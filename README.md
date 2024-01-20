# Spotify Streams Analysis

## We created a logistic regression model to predict the success of a song based on various metrics, such as danceability, liveliness, energy, etc. A song was considered a success if it received more than the average streams, which we calculated from our dataset. A success was denoted with a "1", otherwise it received a "0". This metric was saved into a new column "song_success". 


## In my model, we used the data from the Logistic Regression model and then I was able to improve on the accuracy. we used the same features and I was able to make a Random Forest Classifier and was able to predict a 0.91 accuracy. We even noticed how some of the features seemed to be more important than other which may have also impacted the decision to determine whether a song would be successful or not.

![classification_report_for_the_random_tree_classifier](https://github.com/ppatel0910/project_2/blob/main/visuals/radnomtrieeclassifer.png)

## Linear Regression description here
![line_graph_for_linear_regression_model](https://github.com/ppatel0910/project_2/blob/main/visuals/Screenshot%202024-01-20%20155528.png)

![scatter_plot_for_linear_regression_model_based_on_stream#_and_the_year](https://github.com/ppatel0910/project_2/blob/main/visuals/linearregressionscatter.png)