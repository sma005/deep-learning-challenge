# deep-learning-challenge
Overview of the analysis: Explain the purpose of this analysis.
This challenge's purpose is to take data points and see if the model can predict whether or not a fundraiser will be successful.

Results: Using bulleted lists and images to support your answers, address the following questions:

**Data Preprocessing**

What variable(s) are the target(s) for your model?
* The target is the "IS_SUCCESSFUL" column. "1" means the campaign was successful. "0" means not successful.

What variable(s) are the features for your model?
* All of the other data in this table besides the target is categorical data that should be used (with the exception of the EIN, name, or target).

What variable(s) should be removed from the input data because they are neither targets nor features?
* We didn't need the EIN or the name.


**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* I chose 17 and 3, because after running the model with a higher number of nodes, 17 and 3 had the least bias according to the graphs in the h3 file. 
* The image "Deep-Learning_Layer_01.png" shows the bias with the lowest amount (17) for the first node
* The image "Deep-Learning_Layer_02.png" shows the bias with the lowest amount (3) for the second node

Were you able to achieve the target model performance?
* No

What steps did you take in your attempts to increase model performance?
* I used high number of nodes the first time (20), and then used the number of nodes that had the lowest bias according to the graphs.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
* A different model using scikit could possibly be used. It also offers different solutions that may be able to predict accuracy differently.
