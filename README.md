# Project-INT246
# Summary
This Project consists of predicting the location of Separation parameters.

This is done by first taking one data set from the directories of all the four locations and labeling them with nominal values as follows:

1 -> corridor
2 -> hall
3 -> lab
4 -> lobby

Then these files are furthur combined and shuffle in one file and then from that file all the separation factors are catagorised as variable x and the target(location) is assigned variable y. These are then split into training and testing parts and then passed into the classifier which fits them into the KNN algorithm
