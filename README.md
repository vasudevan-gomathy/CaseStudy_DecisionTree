# CaseStudy_DecisionTree

## Summary

A Decision Tree is a supervised machine learning algorithm that can be used for both Regression and Classification problem statements. It divides the complete dataset into smaller subsets while at the same time an associated Decision Tree is incrementally developed.

The final output of the Decision Trees is a Tree having Decision nodes and leaf nodes. A Decision Tree can operate on both categorical and numerical data.

![image](https://user-images.githubusercontent.com/85822284/204125612-776262f3-e4bc-463e-ad95-56cb032e72eb.png)


Some of the popular algorithms used for constructing decision trees are:

 - ID3 (Iterative Dichotomiser): Uses Information Gain as attribute selection measure.

 - C4.5 (Successor of ID3):  Uses Gain Ratio as attribute selection measure.

 - CART (Classification and Regression Trees) – Uses Gini Index as attribute selection measure.
 
 ## About the dataset
 
 This dataset contains information of users in a social network. Those informations are the user id the gender the age and the estimated salary. A car company has just launched their brand new luxury SUV. And we're trying to see which of these users of the social network are going to buy this brand new SUV And the last column here tells If yes or no the user bought this SUV we are going to build a model that is going to predict if a user is going to buy or not the SUV based on two variables which are going to be the age and the estimated salary. So our matrix of feature is only going to be these two columns. We want to find some correlations between the age and the estimated salary of a user and his decision to purchase yes or no the SUV.
 
 ## Evaluating the Model
 
 The below Confusion Matrix evaluates the Decision Tree Model:

![image](https://user-images.githubusercontent.com/85822284/204125742-e3f65f5e-fd71-442d-ab16-36be11829daa.png)

## Visualizing the Model

**Visualize the Training Set results:**

![image](https://user-images.githubusercontent.com/85822284/204125768-2eb90550-0ca8-4ff2-aa77-dcfd023f0277.png)


**Visualize the Test Set Results:**

![image](https://user-images.githubusercontent.com/85822284/204125780-fb38cc72-88ef-4caf-8fff-c7376df92f41.png)


