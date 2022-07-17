# Ad-Clicker-Predictor

**Overview**

In this project, I have worked on an advertising data set from Kaggle, indicating whether or not a particular internet user clicked on an Advertisement. I have created a logistic regression model that will predict whether or not they will click on an ad based off the features of that user.

The Data Set is from Kaggle: https://www.kaggle.com/datasets/rizdelhi/my-datasets

This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

# EDA
**Area Income versus Age**

![image](https://user-images.githubusercontent.com/89356811/179401196-0c823b57-c0e4-44d4-ad01-95fb572111e8.png)

**'Daily Time Spent on Site' vs. 'Daily Internet Usage'**

![image](https://user-images.githubusercontent.com/89356811/179401219-4f261883-6d52-4a9b-b255-f41c59a37e45.png)

# Metrics
              precision    recall  f1-score   support

           0       0.97      0.99      0.98       171
           1       0.99      0.97      0.98       159
           

**Confusion Matrix**

[[170   1]

 [  5 154]]
 
**Accuracy**

98.2
