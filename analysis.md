# Charity Funding Predictor Analysis

       ) ))
      ( ((  /)
     ,-===-//
    |`-===-'|
    '       '
     \_____/
     `-----'
A binary classifier that is capable of predicting whether applicants will be successful if funded.


### **Overview:**
Explain the purpose of this analysis.

# <img src="./resources/clusters.png" />

### **Results:**
  * Data Preprocessing
    * What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL
    * What variable(s) are considered to be the features for your model? CLASSIFICATION, APPLICATION_TYPE
    * What variable(s) are neither targets nor features, and should be removed from the input data? 'EIN', 'NAME' are should be removed from the input data because they are are neither targets nor features.
  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * Were you able to achieve the target model performance?
    * What steps did you take to try and increase model performance?

	model w/o opt - 0.7375
	model w/ opt1 - 0.7383 less features
	model w/ opt2 - 0.7328 less features than opt1, activation='selu'
	model w/ opt3 - 0. doubled nodes from opt1
	
	
### **Summary:**

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.