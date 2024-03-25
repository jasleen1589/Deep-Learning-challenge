# Deep-Learning-challenge

The purpose of this analysis is to utilize Deep Learning to predict the success of organizations like Alphabet Soup. The model uses various features of the organization and classifies whether the organization will be successful or not in its endeavors.

Data Pre-processing: The variables such as "Target" and "Feature" were defined along with the variables that were removed were acknowledged. 
The "Target" Variable is "Success" which indicates whether an organization was successful based on Alphabet Soup's funding.
The "Feature" Variable include the remaining variables such as "Organization Type", "Use of Funds", and the "Grant Size".
"EIN" and "Name" were removed from the input data as these variables did not contribute to the model's predictive behavior.

Compiling, Training, and Evaluation the Model: Functionalities of neurons, layers, activation functions, model performance, and optimization attempts were analyzed.
Neurons,layers, activation functions: Relu function activation was used to activate the functionality and to introduce non-linearity. The neural network was designed with an input layer which also reflected the feature variables with 80 and 30 neurons.The output layer had a single neuron with a sigmoid activation function which is needed for binary classification.
Model Performance: The model's accuracy was "Accuracy: 0.73" which is less than 75% and it can be stated there is room for improvement to achieve optimized results for this model. 
Optimization Strategies: Other models such as the Random Forest Classifier or Gradient Boosting Machines can help improve accuracy. The neural network itself can be improved by adjusting layers, neurons, activations functions, or training process, or even considering other machine learning models and approaches. 

Summary: 
Overall, the model performance was below 75% target performance needed. The model had an accuracy of 73% and to reach the target performance, it can be said that either an alternative machine learning model can be used or changes can be made to the activation method. Changes to neurons or layers can also be considered to achieve the goal of target performance.
Also, since there is mixed data involved, using more sophistivated preprocessing and feature selection can also have an impact on improving predictive signals. Hyperparameter tuning can also be used to understand and train the parameters such as learning rate, batch size, and epochs which can also lead to improvements.
And finally, other machine learning models such as Random Forest or Gradient Boosting can also be used to achieve results of 75% target or higher as they can work better with complex data types and are built to handle better understanding and influencing of the organizational success. 
