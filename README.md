# House-Price-Prediction
House Price Prediction using Ridge Regression

Dataset info:
![1](https://user-images.githubusercontent.com/76995828/152630749-e32d7c22-2275-46c8-8afe-6050b67ae711.png)

Dataset:
![2](https://user-images.githubusercontent.com/76995828/152630843-0eb55602-842b-4052-be00-baac40d2f8b0.png)

Using some differnt types of ploting to visualize this dataset-----
![3](https://user-images.githubusercontent.com/76995828/152631026-0e00694b-6e58-479d-aea6-32b2cdfa0a06.png)

Fit a linear regression model using the longitude feature 'long' and caculate the R^2 value.
![image](https://user-images.githubusercontent.com/76995828/152631100-87cd2a15-4f2b-4411-a0d8-fff453041059.png)

Fit a linear regression model to predict the 'price' using the feature 'sqft_living' then calculate the R^2 value.
![image](https://user-images.githubusercontent.com/76995828/152631138-9f8c11b8-e0f9-45bc-b25b-d1e6c945f712.png)

Fit a linear regression model to predict the 'price' using the list of features: floors, waterfront, lat, bedrooms, sqft_basement, view, bathrooms, sqft_living15, sqft_above, grade, sqft_living. Using this features and price we used a linear regression model and calculate R^2 value. After that we use the list to create a pipeline object to predict the 'price', fit the object using the features in the list features, and calculate the R^2 value. After the calculation of all R^2 value, we compared the all R^2 values to know which gives the best R^2 value. Here we use a bar plot to show to different R^2 values in a graph.

![image](https://user-images.githubusercontent.com/76995828/152631514-5049c503-841d-46f8-9668-be0837edfbb9.png)

Split our dataset into two parts, one is test and another is train. Here we use 85% of data in train part and 15% is used in test. After the slpiting of data we create a ridge regression object using the training data and predict the values. Then we create a second order polynomial transform on both the training data and testing data then create a ridge regression function and predict the value. After that we compare the two R^2 values using bar plot.

![image](https://user-images.githubusercontent.com/76995828/152631804-7182f220-f221-48d3-952f-3ea6087ea228.png)
