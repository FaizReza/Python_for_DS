# A. Project Description (Abalone Age Prediction)

Here, we will go through the current scenario of the company associated with this project

AB Fresh Supply Co. Ltd.: Company Introduction

Your client for this project is an Abalone Producing and Processing company.

They want to supply the highest quality of abalones with a good price through direct transactions with fish farms. They have experience in exporting abalones to North America as well as South East Asia. To find the highest quality abalones, they need to analyze their measurements. One of the key measurements in this process is the age of the abalone.

Current Scenario The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope. By adding 1.5 to the number of rings, we get the abalone’s age in years.

# B. Problem Statement

In this step, the problem statement of the project and the project deliverables are defined. Please refer the video in order to get a good understanding of what to expect in this step. After that, you can go through the text below to get the specific details related to this project.

The current process suffers from the following problems: Since the age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope. This becomes a quite boring and time-consuming task.

The company has hired you as data science consultants. They want to automate the process of predicting the age of abalone from other physical measurements rather than doing this manual work.

#### Your Role

You are given a dataset containing the physical measurements of abalones. Your task is to build a regression model using the dataset. Because there was no machine learning model for this problem in the company, you don’t have a quantifiable win condition. You need to build the best possible model.

#### Project Deliverables

    Deliverable: Predict the number of rings for each abalone.
    Machine Learning Task: Regression
    Target Variable: Rings
    Win Condition: N/A (best possible model)

#### Evaluation Metric

    The model evaluation will be based on the RMSE score.
    To learn about RMSE’s Python implementation, please visit this link.

# C. Data Description

"This step provides an in-depth description of the dataset associated with this project.

The dataset contains all the necessary information about the abalones like their sex, length, diameter, height, weight, etc. The column Rings is also present in the dataset which is a measure of the age of the abalone. By adding 1.5 to the number of rings, we get the abalone’s age in years.

This is the data that we have to predict for future samples. The dataset is divided into two parts: Train, and Test sets.

##### Train Set:

    The train set contains 3341 rows and 10 columns.
    The last column Rings is the target variable.

##### Test Set:

    The test set contains 836 rows and 9 columns.
    The test set doesn’t contain the Rings column.
    It needs to be predicted for the test set.

##### Sample Submission File: A sample submission csv file named sample_submission.csv is also provided with the dataset. This sample submission file contains the format of the final predictions submission csv file that you need to upload via the Upload Submission tab.

####Id    Feature 	Description
01 	ID 	Unique Id of the sample
02 	Sex 	The sex of the abalone (M, F, and I (infant)).
03 	Length 	Longest shell measurement (mm).
04 	Diameter 	Diameter of abalone perpendicular to length (mm).
05 	Height 	Height of abalone with meat in the shell (mm).
06 	Whole_weight 	Weight of the whole abalone (grams).
07 	Shucked_weight 	Weight of the meat of abalone (grams).
08 	Viscera_weight 	Gut weight (after bleeding) of the abalone (grams).
09 	Shell_weight 	Weight of the abalone after being dried (grams).
10 	Rings 	Number of Rings in the abalone.
