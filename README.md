# TCGenForFL

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)
[![GitHub version](https://badge.fury.io/gh/boennemann%2Fbadges.svg)](http://badge.fury.io/gh/boennemann%2Fbadges)

[Bing](http://wwwen.uni.lu/snt/people/bing_liu) is the author and responsible for the maintenance of this github repo. Contact him for any further queries.

## Overview

This github repo is created for releasing our experiment data, as well as the training and testing set data for our prediction models.


## Structure

The directories of this repository and their meaning are as follows:

- FaultLists.md:   a description file for faults which we used in our experiment in our industrial case studies. We are sorry that we cannot release our industrial subjects because of the related collaboration contract policies between us and our industrial partner. 

- DataFolder.zip: Containing both important experiment data files (rankings), and the related data file that we used to build and test our prediction models (and 3-fold cross validation process).

## Note

###Naming convention
In order to help you to understand the files we released in the .zip file. Here are the related rules of our naming convention:

- ExpData:   Experiment Rankings;

- PredData: related files for prediction model;

- AbVe:  is the model called **MGL** in our paper;

- AnsaugSystem/Ans: is the model called **MA** in our paper;

- Zyl: is the model called **MZ** in our paper;

- AF*n* : the *n*th faulty version;

- HCRM1: folder of the data of fitness: DBB;

- HCRM3: folder of the data of fitness: Density(in prediction related file, we called: Ent);

- HCRM4: folder of the data of fitness: Dissimilarity;

- R*n* (folder name): folder of the data for the *n*th trial experiment;

- *n*thRanking.csv: the *n*th round ranking; please notice that 0thRanking.csv is the **initial** ranking;

### Prediction

- Currently, we use [R Script](https://www.r-project.org/) to do all the feature computing work and automated prediction.

- Important function in R are: rpart(... (minsplit=50)...), and predict(...);

- For the final accuracy statistics work, we use Microsoft Excel (click-based) operations. We have not created any Excel script for this because the operations are only a few and not difficult if you are familiar with Microsoft Excel.

- Decision trees generated has already been included in the DataFolder.zip.

##Acknowledgement

Thanks for the help and support from our industrial partner [Delphi Automotive Systems Luxembourg](http://www.delphi.com/about/locations/luxembourg).

## Feedback

All (seems-like)bugs, anything unclear/need to be improved, requests, feedback, etc., are welcome. Please contact: [Bing](http://wwwen.uni.lu/snt/people/bing_liu) by email.
