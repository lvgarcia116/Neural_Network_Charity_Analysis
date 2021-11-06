# Neural_Network_Charity_Analysis
## Overview of analysis:
This project is intended to analyze a CSV containing over 34,000 organization that have received funding from Alphabet Soup over the years. The purpose of this analysi is to use ML and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results:

Data Preprocessing
- The variable that was considered the target for this model is the IS_SUCCESSFUL column 
- The feature variables were all of the other column names except the column mentioned above
- The variables EIN & NAME were removed from the dataset

Compiling, Training, and Evaluating the Model
<img width="784" alt="Screen Shot 2021-11-06 at 1 38 44 PM" src="https://user-images.githubusercontent.com/86024512/140618794-13404b74-1225-49f2-b332-e9aead71629c.png">

- The neural network model consissted of 30 nodes in the first layer, 90 nodes in the second layer. The action function in the first layer was "relu" and the second layer was "sigmoid"
- The accuracy for this model was 43% therefore I was not able to achieve the target model performance.
- The steps I took to try and increase model performance was adding a third hidden layer with the activation function "sigmoid" and decreased the epochs to 40. However, this only increase the accuracy of the model to 60%. 

<img width="784" alt="Screen Shot 2021-11-06 at 1 38 44 PM" src="https://user-images.githubusercontent.com/86024512/140618822-5a5d74c8-3487-4908-af76-11c2cd6013be.png">

## Summary: 
Multiple attempts were made to increase the model performance, however the accuracy of the model increased to 60% upon adding a third hidden layer with the activation function "sigmoid" and decreasing the epochs to 40. A recommendation would be to change the activation function of the hidden layers, and/or to decrease the number of bins used in the analysis. 
