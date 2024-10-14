# deep-learning-challenge

Overview
 
 This analysis aims to build a deep learning model to predict whether a charity application will be successfully funded based on various features of the application.

Results
 
 Data Preprocessing:

- Target Variable:
IS_SUCCESSFUL (1 = funded, 0 = not funded)

- Feature Variables:

Application type, classification, income amount, and other relevant characteristics.
 
 - Variables to Remove:
EIN and NAME (not useful for predictions).

Model Development

Architecture:

3 layers:

 - First hidden layer: 80 neurons (ReLU activation).
 - Second hidden layer: 30 neurons (ReLU activation).
 - Output layer: 1 neuron (Sigmoid activation).

Performance:

 Achieved accuracy: 0.6414 

Improvements:

 adjusted the model's layers and neurons to make it work better. I also added techniques like dropout and batch normalization to prevent overfitting, and I trained the model longer to improve its accuracy.

Summary:

 The model predicts if a charity application will get funded based on its features. It achived an accuracy of 0.6414, showing it works well, we can make it even better by using simpler models like Random Forest or Gradient Boosting for easier undrestabding and better results.


Recommendation:

 Use Random Forest or Gradient Boosting for better accuracy and easier interpretation. These methods often outperform deep learning, especially with smaller datasets, and require less tuning. They also highlight which features most influence funding predictions.

