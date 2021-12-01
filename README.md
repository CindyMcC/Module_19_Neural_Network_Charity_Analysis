# Module_19_Neural_Network_Charity_Analysis
UNC Bootcamp - Module 19

# Overview
This project used a provided dataset to predict whether an organization would be successful if funded by Alphabet Soup foundation.  The TensorFlow platform in Python was used to employ neural networks and deep learning to process the data.

# Results
## •	Data Preprocessing<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The dataset contained an “Is Successful” field that indicated the success of past donations. This field was used as the target of the processing.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The features for the model were determined to be the following columns of data:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The EIN and Name columns were not needed for the model and were removed from the dataset.

## •	Compiling, Training, and Evaluating the Model<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The original model had two hidden layers, both using the activation function ReLU.  The first layer had 80 neurons and the second had 30.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The model did not reach a target accuracy of 75% and would not help in determining which charities would succeed. Adjustments were made to the model to improve the percentage.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	The first optimization attempt changed the number of epochs from 100 to 150.  The second attempt increased the number of neurons in the hidden layers to 100 and 50.  The third attempt added a third hidden layer, changed the neurons to 80/40/20 for the layers, and decreased the epochs to 50.


# Summary
None of the four models were able to reach the target performance of 75% accuracy and further adjustments may not be adequate to train the model.  A different approach should be tried, such as using Random forest classifiers.  Working with multiple smaller models may produce a higher accuracy rate.

