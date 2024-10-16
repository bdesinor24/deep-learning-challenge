Overview of the analysis: Explain the purpose of this analysis.
This analysis is modelling charitable contribution.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
y = EIN_NAME_APPLICATION_DF['Is Successful'].values
X = EIN_NAME_APPLICATION_DF.drop('Is Successful', axis=1).values

What variable(s) are the features for your model?
number_input_features = len(X_train[0])

What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model
- EIN
- NAME

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
