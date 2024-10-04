# deep-learning-challenge

**Overview**
- The purpose of this project was to analyze/explore a feature dataset for a nonprofit foundation's funding program in order to create a deep learning binary classification model.

**Results**
- Input variables were all columns within the dataset without 'EIN', 'NAME' and the labeled outcome column of 'IS_SUCCESSFUL'
- Target variable was the binary (0 or 1) column 'IS_SUCCESSFU'
- Removed variables were the 'EIN' and 'NAME' columns
- Initial model structure: Input layer, hidden layer one with 80 neruons, hidden layer two with 30 neurons, relu activation functions, output layer with sigmoid activation function, 100 epochs
- Optimized model structure: input layer, hidden layer one with 120 neurons, hidden layer two with 50 neurons, hidden layer three with 50 neurons, hidden layer four with 50 neurons, relu activation functions, output layer with sigmoid activation function
- Unable to achieve target performance of 75% accuracy
- In an effort to achieve optimal model performance, the number of neurons in each layer was increased, the number of overall layers were increased, the number of epochs were increased and different activation functions (tanh) were explored

**Summary**
  - The initial and optimized models achieved an accuracy metric of 72-73% and loss metric of 53-55%
  - Further improvement could be derived from using a feature importance approach, removing the least important features within the model as well as uzing this information to enhance data collection to build a more predictive model.
