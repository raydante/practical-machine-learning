
# Coursera Practical Machine Leaning course project

The goal of this project is to predict the quality of how the subjects performed  an exercise from readings from activity monitor readings.

Any method was allowed and I used Random Forests.  

Split the data into training and test sets.  I then used 10 fold cross validation to choose the number of trees in the random forest.  Then I built a model using random forests of 51 trees each. Then, using the test set, I estimated the out of sample error rate for the model.

Finally, I used the model to predict the classe of the 20 samples supplied.

