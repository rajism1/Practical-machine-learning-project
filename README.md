# Practical-machine-learning-project
Contains final project of coursera practical machine learning course.

In this project, the main goal is to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants and predict the manner in which they did the exercise.\
They were asked to perform barbell lifts correctly and incorrectly in 5 different ways.\
There is the "classe" variable in the training set which describes the manner in which participants exercised.

Data:- \
The training data for this project are available here:\
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv \
The test data are available here:\
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


Project started with removing all columns containing more than 95% of NAs or Blanks.\
then also removed some columns like timestamps,username etc. which doesnot significantly impact our model.\

Have trained our model using random forest and predicted based on the model built.
