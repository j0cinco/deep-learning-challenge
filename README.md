# deep-learning-challenge

Overview of the analysis: the purpose of this exercise was to review a csv (using python, scikit, and tensorflow) that contained information about organizations who received funding from Alphabet Soup. I loaded the csv into a dataframe,dropped some non-essential columns, designated a cut-off value, classified values into bins, split the data into train and test groups, and utilized StandardScaler.  Finally, I compiled, trained, and evaluated the model three times.

Results:

Data Preprocessing

-Which variable was the target for this model? IS_SUCCESSFUL
-Which variable was the features for the model? APPLICATION_TYPE(s)
-What variables were removed from the input data because they are neither targets nor features? EIN, NAME, STATUS, SPECIAL_CONSIDERATIONS, and ASK_AMT


Compiling, Training, and Evaluating the Model

-How many neurons, layers, and activation functions did I select for my neural network model, and why? 2 hidden layers and one outcome layer. I used relu, sigmoid, and tanh. Adding additional layers would not have yielded any different results. 

-Was I able to achieve the target model performance? The target was 75% accuracy, I fell just short at 72-73%

-What steps did I take in my attempts to increase model performance? Utilized various activation function types and attempted different neuron numbers.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

As I said previously, I did not obtain the targeted accuracy level. This likely could've been due to the fact that I did not add additional layers when using the various activation types. 