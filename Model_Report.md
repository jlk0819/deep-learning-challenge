
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

*Data Preprocessing*

1.  What variable(s) are the target(s) for your model?
- 'IS_SUCCESSFUL' is the target 
2.  What variable(s) are the features for your model?
- Every other column are the feature vars from application_df, dropping the 'IS_SUCCESSFUL' defined it.
3.  What variable(s) should be removed from the input data because they are neither targets nor features?
- Both 'EIN' and 'NAME' columns were dropped/removed, as they were 'fluff' data.

*Compiling, Training, and Evaluating the Model*

1.  How many neurons, layers, and activation functions did you select for your neural network model, and why?
- 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 in attempt one. Random tries from which to build upon in additional trials.
2.  Were you able to achieve the target model performance?
- I was not able to achieve the 75% model accuracy target, it would hit 74% but not the full 75.
3.  What steps did you take in your attempts to increase model performance?
- Added layers, removed columns, added hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy, removing more data would begin to prove ineptness of data. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The deep learning model demonstrated an accuracy of approximately 73% in addressing the classification task. To enhance predictive performance, it is crucial to improve the underlying correlation between input features and output labels. This can be achieved through more rigorous data preprocessing, including advanced data cleaning techniques, and by exploring alternative model architectures and activation functions. An iterative approach, involving systematic refinement of these parameters, is expected to yield substantial improvements in model accuracy.
