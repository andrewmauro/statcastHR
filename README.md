# statcastHR
A model to predict the probability that a batter hits a home run in a given plate appearance, given a dataset from MLBAM's Statcast.

The attached code takes a data set of statcast data and uses it to predict the probability of a batter hitting a home run using a rolling average of pitch results. Statcast data contains a variety of metrics related to pitch events that occur during major league games, including pitch velocities, the result of each pitch (swinging strike, ball, line drive, foul ball, etc.), and exit velocities and launch angles for batted balls. The below code takes these features and organizes them so that a predictive model can be generated to predict a batter's likelihood of hitting a home run.
