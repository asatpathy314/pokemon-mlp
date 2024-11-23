# Project Proposal

## Group members

1.  ***Abhishek Satpathy (cqa3ym)***

2.  ***Mark Do (mft6zc)***

3.  ***Guy Scafidi (tet8bx)***

## Project Title

***Pokémon Classifier: Utilizing Bayesian Hyperparameter Optimization to Find the Optimal hyperparameter Configuration for Pokémon type classification leveraging a Multi-Layer Perceptron (MLP).***

## Description of project

***This project aims to investigate how different activation functions in multi-layer perceptron (MLP) networks affect classification performance. Specifically, we will focus on classifying a Pokémon's type from its sprite using a public dataset and comparing the error rates of various activation functions (e.g., ReLU, Sigmoid, Tanh). The goal is to identify which activation function yields the best classification results under similar conditions.***

1.  What dataset(s) will you use
    - ***We will use the following dataset of [Pokémon](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types/data?select=pokemon.csv).***

2.  What algorithm(s) will you test
    - ***We will test the effects of different activation functions (ex: ReLU, Sigmoid, Tanh) for MLP networks on error rate in pokemon classification.***
      
3.  What hypothesis are you testing or what experiment are you
    performing
    - ***The experiment we will be performing will be testing different activation functions for a multi-layer perceptron classification on different pokemon types. After testing different         types of the classification functions, we will determine the function which had the best optimization of pokemon types.***

4.  What code will use write yourself vs. what is already provided in a
    library that you will call
    - ***We will have to develop a pipeline to clean, split, and validate the data using the `pandas` library mixed with some `numpy`. This includes deciding how to handle missing values and encoding categorical variables. 
    Then, we will use the MLPClassifier from sklearn but customize it by iterating over different activation functions (relu, tanh, logistic) to compare their performance. In terms of visualization, we'll write out the data transformations and configuration ourselves with the help of `matplotlib`.***

## Roles

***1. Abhishek Satpathy:***
- ***Implementing the MLP model using scikit-learn.***
- ***Will test different activation functions (ReLU, Sigmoid, Tanh).***
- ***Will also handle model training and tuning hyperparameters.***
- ***Will create visualizations to explain how each activation function impacts model performance.***

***2. Mark Do:***
- ***Collecting and preprocessing the Pokémon dataset.***
- ***Will write code for cleaning the data (handling missing values, normalizing features).***
- ***Will also create visualizations that give an overview of the dataset and ensure it's ready for training.***

***3. Guy Scafidi:***
- ***Comparing the outputs from different activation functions.***
- ***Will analyze and summarize the pros and cons of each activation function in terms of accuracy, training time, and convergence.***
- ***Will also help with final report writing and presenting results.***
