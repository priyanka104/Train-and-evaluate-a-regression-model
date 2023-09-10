# Train-and-evaluate-a-regression-model

What is regression?

Regression works by establishing a relationship between variables in the data that represent characteristics—known as the features—of the thing being observed, and the variable we're trying to predict—known as the label.

Recall our company rents bicycles and wants to predict the expected number of rentals in a given day. In this case, features include things like the day of the week, month, and so on, while the label is the number of bicycle rentals.

To train the model, we start with a data sample containing the features, as well as known values for the label; so in this case, we need historical data that includes dates, weather conditions, and the number of bicycle rentals.

We'll then split this data sample into two subsets:

A training dataset to which we'll apply an algorithm that determines a function encapsulating the relationship between the feature values and the known label values.
A validation or test dataset that we can use to evaluate the model by using it to generate predictions for the label and comparing them to the actual known label values.
The use of historic data with known label values to train a model makes regression an example of supervised machine learning.
