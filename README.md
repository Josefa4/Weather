Project proposal - Group 54
Project title: Weather Pattern Evolution

Rachel Dupuy, student number: 16326948

Josefa Kubitová, student number: 16329260

1. Motivation: What problem are you tackling? 
We plan to analyze monthly weather data from Valentia Observatory, Co Kerry, 
to see long term changes in weather patterns and be able to predict how they might evolve in the future. 
As weather patterns change all over the world due to climate change, 
being able to predict these changes is key in preparing for those that we are too late to avoid.

2. Dataset: What data will you use and how will you collect it?
     Our plan is to use open source data, 
and we intend to collect data from the data.gov.ie website: 
https://data.gov.ie/dataset/valentia-observatory-monthly-data 
 Our goal is to train a model on the long term changes in the weather 
in order to see if it is possible to predict certain patterns that may arise in the future due to climate change.
 While we obviously expect rainfall and temperatures to change most significantly, 
we will also check whether any perceptible change occurred in other measured categories.

3. Method: What machine learning techniques are you planning to apply or improve upon?
    We plan on using various types of regression and comparing them to one another as well as a baseline model 
which simply predicts a repetition of the previous year. 
Lasso regression might choose only a few variables to base its estimates on, 
it will be interesting to see which variables it might prefer.
 Ridge regression on the other hand, will keep these variables and might therefore come to a different conclusion.

4. Intended experiments: What experiments are you planning to run? How do you plan to evaluate your machine learning algorithm?
            First and foremost, we will be experimenting with various types of regression model, 
in order to find out which one is most optimal for our needs. 
Following that, we hope that we may be able to spot correlation between certain pieces of data that might not be entirely intuitive, 
such as rainfall and temperature, thus then we may be able to experiment with the omission or inclusion of certain pieces of data and deduce how it will impact the model's predictions. 
Our main goal is to predict the evolution of future weather patterns and how these are impacted by climate change. 
We will then compare our trained model against a previously defined baseline model to measure its accuracy and efficiency.

