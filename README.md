# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to use machine learning and Neural Networks to determine whether applicants will be successful if funded by Alphabet Soup.

## Results

Results can be broken down into the following

### Data Preprocessing
* A target array for this model is the IS_SUCCESSFUL column data, as that is a yes/no output
* Features data included all columns not dropped or the IS_SUCCESSFUL columns
* The dropped columns that would not be beneficial in this analysis are the EID and NAME columns

## Compiling, Training, and Evaluating the Model
* In the original Machine Learning Model, 80 neurons were used in the first layer, followed by 30 in the second:
![image](https://user-images.githubusercontent.com/80076110/126927457-b03f1bcb-6d3d-45fc-baeb-cf3c15609b15.png)
* Target model performance came close in the original model
* ![image](https://user-images.githubusercontent.com/80076110/126927501-f5710107-b794-42c3-be9e-19a73a74d601.png)
* However, in the optimization models, the accuracy decreased:
* Attempt 1
![image](https://user-images.githubusercontent.com/80076110/126927636-d97c4f26-a3fc-4485-82f4-792c8c8b7973.png)
* Attempt 2
![image](https://user-images.githubusercontent.com/80076110/126927647-617467a7-68db-4efe-95b8-9cc88f5f8ed3.png)
* Attempt 3
![image](https://user-images.githubusercontent.com/80076110/126927653-651f37a5-145a-4cab-ae6e-2bf23c45af1a.png)


