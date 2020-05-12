# Netflix Recommendation System

# Complete Problem Statement

## Goal 

Analyze the NETFLIX data using SPARK  and, based on the outcomes of this analysis, develop a feasible and efficient implementation of the collaborative filtering algorithm in SPARK. 


The given datasets are Trainingsets.txt and Testingsets.txt having 3 features namely user ID, Movie ID and the ratings. 

## Step 1 : Implementation 

Implement the approach in a Jupyter Notebook using PySPARK on an AWS EMR cluster gor getting the rating predictions and evaluating those ratings by comparing them to the provided true ratings.


### Analyzing the data

In this problem you will analyze the input data to plan out an efficient  implementation of your approach. For (a) and (b) you must use SPARK in Jupyter Notebooks running on AWS EMR. Remember to develop and test your implementations on a small subsample of the data!

(a) In order to be able to evaluate your approach the goal of your project is to predict the ratings for all user-item pairs in the test set (TestingRatings.txt). How many distinct items and how many distinct users are there in the test set (TestingRatings.txt)? 

(b)The collaborative filtering approaches lives from finding many similar users (for a user-user model) or many similar items (item-item model): 

• user similarities are measured by overlapping items
• item similarities are measured by overlapping users 

### Collaborative Filtering Implementation

Implement a collaborative filtering algorithm using the 3.25 million ratings provided in the TrainingRatings.txt file as given utility matrix. Finding the k-most similar items or users should be implemented in a Jupyter Notebook using PySPARK.

Some of the approaches :

• similarity measure (JACCARD, COSINE, CORRELATION, other?)

• number of similar users k 

• prediction method (weighted or un-weighted average) 

• you may threshold the ratings 

• you may normalize the ratings or not 

• user-user model or item-item model 

## Step 2 : Execution and Evaluation 

(a) Run your implementation to predict the ratings for all (or as many as possible) user-item pairs in TestingRatings.txt. 

(b) For evaluation, compute the Mean Absolute Error and the Root Mean Squared Error for your predictions. 
 
## Step 3 : Does your approach work for your own preferences?

Add yourself as a new user to the data set. To do this, you will need to create a new, unique user ID for yourself. Select some movies that you have seen among those in the training set, and add your ratings for those. Use your approach to output predictions for the movies you haven’t rated, and rank those in decreasing order of the rankings.

## My approach

Check for the final_report and src in this Repo.  