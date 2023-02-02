# Module 20 challenge: ML & Neural Networks

**Overview:**
The objective of this analysis is to predict the success of applicants applying for funding from Alphabet Soup. The analysis will leverage machine learning and neural networks.The dataset is provided by Alphabet Soup with 34K that have received funding over the years. 

**Results:**
Data processing -
The target variable is ‘IS_SUCCESSFUL’

The features variables are:
STATUS
ASK_AMT
APPLICATION_TYPE
INCOME_AMT
SPECIAL_CONSIDERATIONS
USE_CASE
AFFILIATION

The variables that are not targets or features are ‘EIN’ and ‘NAME’ and both are removed.

Compiling, training and evaluating the model - 
The initial attempt, 2 layers were applied with 80 and 30 neurons along with the ‘relu’ activation function for both layers and ‘sigmoid’ for the output layer.  The ‘relu’ function was chosen because of its simplifying output. 
The target model performance is 75% and I was unable to achieve the target. My best result was 73.7%.
The 3 attempts were made to optimize the model. First attempt was by adding an additional layer,  the second attempt was by changing the activation function, and the last attempt was by removing additional data. 
		
**Summary: **
Given the dataset that’s available we are unable to confidently say we can predict the success of the applicants without additional data. We can continue to optimize with various other activation functions, layers, and neurons, perhaps even engineer some additional features to be considered for the model. 

