# deep-learning-challenge
Module 21 Challenge

# Overview:
The purpose of this analysis was to create a model that would predict the success of Alphabet Soup company funding different applicants’ business ventures.

# Results - Data Preprocessing:

The target variable for my model was the "IS_SUCCESSFUL" column, which describes if the money was used effectively.

The feature variables for my model were the following:
- APPLICATION_TYPE —Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested

The variables that are removed because they are neither targets, nor features, are EIN and NAME, since they are identification columns

# Results - Compiling, Training, and Evaluating the Model:

Looking at file, 'AlphabetSoupCharity_Optimization_3, I used 20 neurons, 3 layers, and 41 features for the neural network model. After a few runs and trying different combinations, having more neurons and less layers, would ultimately give me higher accuracy. 

I was not able to get the achieved target model performance, I was only able to reach 73%.

To increase the model's performance, I would increase the number of neurons first, and then drop some of the columns that have only 2 unique values. Then I would increase the number of neurons again.

# Summary
This deep learning model can be optimized further, as it I was not able to reach the 75% performance target. If we were to use kt.Hyperband to find the best model to use, that would be helpful. This way, I could find the best model and then optimize the model.
