# deep-learning-challenge
Module 21 Submission 
Comments are made in the coding file itself. If time permits I will have another more optimized model sooner using the auto optimization method. 

# Report
### Purpose:
The purpose of this analysis is to build a predictive model using neural networks that can determine the success of Alphabet Soup-funded organizations based on various features provided in the dataset.

### Data Preprocessing

What variable(s) are the target(s) for your model?
In the dataset represented by application_df, the target variable I aimed to predict is 'IS_SUCCESSFUL'. This variable indicates whether a charitable organization's application for funding was successful or not.

What variable(s) are the features for your model?
The features used to predict the target variable are comprised of all columns in application_df except for 'IS_SUCCESSFUL'. These features encompass various attributes and characteristics of charitable organizations, which I leveraged to make predictions about their funding success.

What variable(s) should be removed from the input data because they are neither targets nor features?
During data preprocessing, I excluded the 'EIN' and 'NAME' columns from the dataset. These columns were not relevant as either targets or features for our predictive modeling task. The 'EIN' column represents the Employer Identification Number, and the 'NAME' column denotes the name of the charitable organization. While important for identification purposes, they do not contribute to predicting funding success and were therefore removed from our input data.

### Compiling, Training, and Evaluating the Model
In the optimized setup, I chose 64 neurons for the first hidden layer and 32 neurons for the second hidden layer. I chose these neurons because the problem I'm solving is complex and requires the model to learn intricate patterns and relationships in the data, having more neurons in the hidden layers allows the network to capture and represent these complexities.

Were you able to achieve the target model performance?
Unfortunately, I fell short of achieving the target model accuracy of 75% including the second attempt.

What steps did you take in your attempts to increase model performance?
I increased the number of neurons to see if there was an improvement to the models performance. 

### Summary:
I tried to build a neural network model with 10 neurons in the first hidden layer and 6 neurons in the second, but I didn't hit the 75% accuracy target. Despite making various adjustments like changing the amount of neurons, I couldn't reach the desired accuracy. This shows that optimizing models requires a lot of trial and error.