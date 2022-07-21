# Overview
This document provides an overview  of what was done in this logistic regression model to predict customer churn of a telecom company

## All data was imported
![1](https://user-images.githubusercontent.com/79614977/180183647-f59857f5-56f8-464e-975d-7844db1d7bcc.png)

## Data was cleaned up
For example:
- Yes and No were converted to 1 and 0
- Unncessary information was removed
- There were no outliers
- Dummy variables were created
- Object types were converted to necessary types
Before, the data looked like this 
![3](https://user-images.githubusercontent.com/79614977/180184538-2fdd7388-2944-4f0e-84b7-bf00ed105e4e.png)
Afterwards, the data looked like this
![2](https://user-images.githubusercontent.com/79614977/180184594-0b29011a-5664-4d37-b66f-a81c1e00b8a6.png)

## Simple EDA was performed
Some insights were gatheres such as
#### Comparision of various services availed
![4](https://user-images.githubusercontent.com/79614977/180184726-c1137c24-eef2-4325-b231-28d51e6819c5.png)

#### Internet service preference 
![5](https://user-images.githubusercontent.com/79614977/180184741-bf13f0f3-ab14-487f-8298-726fb9ec584f.png)

#### Constract preference
![6](https://user-images.githubusercontent.com/79614977/180184753-b6faf8f5-9d3d-47af-972d-5c2b763988ad.png)

#### Scatter plots to see the distribution of Churn cases
![7](https://user-images.githubusercontent.com/79614977/180184796-c759cc87-1471-4e02-8c5a-83014d5cdf9f.png)

#### Business contribution
If the business were to be divided into 2 categories which generate equal income, then the division line would be approx at 4736.
Customers whose total charges are above 4736 contribute equally to the customers whose total charges are below 4736
![8](https://user-images.githubusercontent.com/79614977/180184814-7e9e31de-199e-42af-9b9e-1d0db02af8ff.png)

## Model building, evaluation
Model was built after thorough RFE and VIF analyses\
![9](https://user-images.githubusercontent.com/79614977/180185582-a28ba30c-17de-4501-96df-ab58c5d01272.png)

Cut-Off was chosen as 0.3 based on sensitivty and specificity analysis of the train case\
![10](https://user-images.githubusercontent.com/79614977/180185743-bcce89a7-1810-465e-b8c6-c2488e8fa634.png)

## Predictions
Predictions were made\
![11](https://user-images.githubusercontent.com/79614977/180188383-1368b92e-0354-46fa-a646-8a698b6ed877.png)

Satisfactory results were obtained on the Test case\
![12](https://user-images.githubusercontent.com/79614977/180186528-852eedfb-d1a1-47c0-a92e-67d76d0c0921.png)
![13](https://user-images.githubusercontent.com/79614977/180186545-9b0052d9-ca3c-4b7c-aac3-aca661918824.png)



