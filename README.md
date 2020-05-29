# Analyzing The Titanic Dataset
Here the Titanic dataset is used with the (rather morbid)
goal of predicting passenger survival, given characteristics such as gender, age, class, etc.

# Result of Analysis
After analyzing this information, we should notice the following:

* Most passengers are in their 20's or 30's .
* Most passengers are male.
* Most passengers are in "Third" class.
* Females have a much higher chance of survival.

# Model Accuracy
And we now we have a model with a 74% accuracy (this will change each time)! Not crazy impressive but decent for our first try.

# Predictions
Now let's see how we can actually use this model to make predicitons.

We can use the .predict() method to get survival probabilities from the model. 
This method will return a list of dicts that store a predicition for each of the entries in our testing data set.
Below we've used some pandas magic to plot a nice graph of the predictions.

As you can see the survival rate is not very high :/
