# Visualizing Multivariate Linear Models in R

## MANOVA: Differences in Group Means / Iris data

Imagine you are a plant biologist and have measurements on four different characteristics of 
different species of a kind of flower.  Can you devise a rule or test to distinguish one species
from another?  If so, what are the weights for the variables that best distinguish among the species?
These were the problems that Edgar Anderson [@Anderson:1935] faced in 1935 when he collected
data on three species of iris flowers found on the Gaspe Penninsula of Quebec, Canada.
The species are "Setosa", "Versicolor", and "Virginica", and he carefully measured the length
and width of two parts of each specimen: the flower petals and sepals (the green  leaves that
enclose the flower).

The iris dataset became famous in the history of statistics because it was shortly used by R. A. Fisher [@Fisher:1936]
to introduce the method of discriminant analysis, which answered Anderson's questions. 
Implicit here was the more basic question:  Are the differences in the means for the species
large enough (relative to with-species variability) to conclude that they differ significantly
on this collection of measurements? This is the question now addressed under the topic of
Multivariate Analysis of Variance (MANOVA).



