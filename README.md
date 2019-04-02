# Facebook-friend-recommendation

## Introduction

This dataset is provided by Facebook as a part of recruiting challenge on Kaggle.
This is a graph link prediction problem. The challenge is to predict missing links in a social nwtwork.

Facebook has not provided the source of the data, we are just given directed social graphs from which some edges have been deleted. Our task is to make predictions for users who might want to follow other users.

## Objective

Given two vertices we need to predict whether there exists a connection between them or not?

## Data Description

#### Data Overview

Source of the data: https://www.kaggle.com/c/FacebookRecruiting

Train data contains 2 columns: 
    - Data columns (total 2 columns):  
    - source_node         int64  
    - destination_node    int64  
    
__This is how our train data looks like__

Source_node Destination_node

1 690569
1 315892
1 189226
2 834328
2 1615927
2 1194519
2 470294
2 961886
2 626040
3 176995

From the data we can say that user1 is a source node, following user690569 which is our destination node.

We have 1862220 nodes & 9437519 directed edges in our dataset
