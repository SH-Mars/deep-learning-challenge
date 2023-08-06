# deep-learning-challenge
Week 21 Challenge: Neural Network

# Overview
The purpose of building this neural network model is to provide a tool for nonprofit foundation, Alphabet Soup, to help select the applicants for funding with the best chance of success in their ventures.

# Results

* Data Preprocessing <br>
    * What variable(s) are the target(s) for your model? <br>
    IS_SUCCESSFUL

    * What variable(s) are the features for your model? <br>
    APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

    * What variable(s) should be removed from the input data because they are neither targets nor features? <br>
    EIN, NAME

* Compiling, Training and Evaluating the Model <br>
    * How many neurons, layers, and activation functions did you select for your neural network model, and why? <br>
    For the model that I started with, there're two hidden layers, with 80 and 30 neurons respectively, and the outcome layer. In the following model optimize attemps, number of neurons and layers were changed to seek a better model performance.

    * Were you able to achieve the target model performance? <br>
    No, it's close but not greater than or equal to 75%, which is the target accuracy we are looking for to this model.

    * What steps did you take in your attempts to increase model performance? <br>
    Adding more layers and neurons.
# Summary
Based on the model we have, it cannot reach the expected accuracy performance. However, we can utilize the best performance model setting with additional data, retraining and reevaluating the model and see how it goes.
