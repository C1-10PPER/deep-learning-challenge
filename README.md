# deep-learning-challenge

* Please refer to deep_learning_challenge.ipynb and AlphabetSoupCharity.h5 for the completed assignment

Please see below for Analysis:

# Overview
The purpose of the anaylsis is to build and train a deep learning model to predict the success of a charity application. 

What variable(s) are the target(s) for your model?
* IS_SUCCESSFUl was the target variable used to indicate whether the application was successful
What variable(s) are the features for your model?
All of the columns, excluding the target, are features that might be used to predict whether the application was successful.
What variable(s) should be removed from the input data because they are neither targets nor features?
* EIN and Name were removed as they are not useful for building a predictive model.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* 3 layers, 2 hidden layers, 1 output layer.
    * First Hidden Layer: 80 neurons, Second Hidden Layer: 30 neurons and Output Layer: 1 neuron.
Were you able to achieve the target model performance?
 The model only achieved a 72% accuracy indicating that there is room for improvement
What steps did you take in your attempts to increase model performance?
* I tried increasing the number of neurons in the first and second layer and tried increasing the number of epochs. But these changes only resulted in a marginal improvement of around 0.5% to 2%.

# Summary:

The model resulted in a 72.59% accuracy with a loss 56.87% which indicates that there is room for improvement with the model to achieve a higher accuracy and a lower loss rate. 
