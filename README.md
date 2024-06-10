# Logistic Regression Project

In this project, I worked with a fake advertising dataset, indicating whether or not a particular internet user clicked on an advertisement on a company website. The goal was to create a model that predicts whether or not a user will click on an ad based on the user's features.

## Dataset

The dataset contains the following features:

- **Daily Time Spent on Site**: Consumer time on site in minutes
- **Age**: Customer age in years
- **Area Income**: Average income of the geographical area of the consumer
- **Daily Internet Usage**: Average minutes a day the consumer is on the internet
- **Ad Topic Line**: Headline of the advertisement
- **City**: City of the consumer
- **Male**: Whether or not the consumer is male
- **Country**: Country of the consumer
- **Timestamp**: Time at which the consumer clicked on the ad or closed the window
- **Clicked on Ad**: 0 or 1 indicating whether the user clicked on the ad

## Project Structure

The project includes the following key components:
1)Get the Data
Read in the advertising.csv file and set it to a DataFrame called ad_data.
Check the head of ad_data.
Use info and describe() on ad_data.
2) Exploratory Data Analysis
Used seaborn to explore the data:
Created a jointplot showing Area Income versus Age.
Created a jointplot showing the kde distributions of Daily Time spent on site vs. Age.
Created a jointplot of 'Daily Time Spent on Site' vs. 'Daily Internet Usage'.
Created a pairplot with the hue defined by the 'Clicked on Ad' column feature.
3) Logistic Regression
Split the data into training set and testing set using train_test_split.
Trained and fitted a logistic regression model on the training set.
4) Predictions and Evaluations
Predicted values for the testing data.
Created a classification report for the model.

