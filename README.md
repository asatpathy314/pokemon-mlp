# Project Proposal

## Group members

1.  ***Abhishek Satpathy (cqa3ym)***

2.  ***Mark Do (mft6zc)***

3.  ***Guy Scafidi (tet8bx)***

## Project Title

***Pokémon Classifier: Determing the optimal Multi-Layer Perceptron (MLP) activation function for Pokémon type classification.***

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
You should also have a rough outline of how you will divide the work
among the group members. This might look something like:

1.  [___Superman is in charge of coding, testing, and creating a
    visualization to explain algorithm A___]

2.  [___Micky is in charge of collecting data, writing the code to clean
    the data, and creating a visualization to give an overview of the
    data___]

3.  [___Harry is in charge of comparing the outputs from
    algorithm A and B and concisely contrasting the pros/cons of each
    algorithms___]

