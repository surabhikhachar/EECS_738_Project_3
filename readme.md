# EECS 738 Project 3: Neural Networks

This is Surabhi Khachar and Andre Kurait's third project for EECS 738, Machine Learning in Spring 2019. For project 3, we designed a neural network to test on two datasets from https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research

The project requirements were the following:

Neural network architectures
1. Set up a new git repository in your GitHub account
2. Pick two datasets from
https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how neural networks can be used to
accomplish the task for the specific dataset
5. Build a neural network to model the prediction process
programmatically
6. Document your process and results
7. Commit your source code, documentation and other
supporting files to the git repository in GitHub

## Data
Data Chosen:
- Iris Flower Species Dataset (https://www.kaggle.com/uciml/iris) 
- Wine classification Dataset (https://www.kaggle.com/brynja/wineuci)

## Neural Network
For this project, we created a simple forward propagation/backpropagation neural network that has three layers. The three layers are the input, hidden, and output layer. The sigmoid function is the activation function used for the forward feeding as it worked well as a non-linear activation function for the dataset. The backpropagation allowed us to update the weights based on the error calculated on each epoch. 
