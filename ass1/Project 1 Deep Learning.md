Project 1: Deep Learning Implementation

CSCI 297: Generative AI

Due: February 7th, 2024, at 11:59PM

In this assignment you will be doing two different projects using sklearn, pandas, NumPy and torch to create a deep learning model. The first problem will walk you through a torch tutorial on how to create a CNN model for the CIFAR-10 dataset. The second problem will be that you create a DL model using torch from scratch to assess the quality of fruit.

TORCH TUTORIAL
In this tutorial you will be given part of the code and then certain places you will be asked to fill in the remaining portions. This code is given to you in jupyter notebook, and you will work through the sections of this tutorial to gain familiarity with torch and building DL models. You are welcome to translate this from jupyter to a normal python script. You will need to make sure your environment is set up to handle torch.

APPLE QUALITY PROBLEM
In this problem you have access to a CSV file that contains data features for determining the quality of an apple. This dataset contains information about various attributes of a set of fruits, providing insights into their characteristics. The dataset includes details such as fruit ID, size, weight, sweetness, crunchiness, juiciness, ripeness, acidity, and quality. The features and a brief description are listed below:

A_id: Unique identifier for each fruit

Size: Size of the fruit

Weight: Weight of the fruit

Sweetness: Degree of sweetness of the fruit

Crunchiness: Texture indicating the crunchiness of the fruit

Juiciness: Level of juiciness of the fruit

Ripeness: Stage of ripeness of the fruit

Acidity: Acidity level of the fruit

Quality: Overall quality of the fruit

You are going to use this dataset to create a DL Model that predicts the quality of the fruit. I would like you to attempt to use a simple feed-forward neural network. Feel free to look back at the tutorial for some tips and tricks for how to prepare the data.

Let me give you some steps that you will need to successfully complete this assignment.

1. Import the data, you should use some type of pandas api call to read in a csv file to a dataframe
2. Provide some information about your data (exploratory data analysis: EDA), there are several pandas functions you can use to do this.
3. Preprocess your data, prepare you input, output vectors / matrices.
4. Normalize or standardize your values such that you are not dealing with various ranges of values for your features
5. Create your neural network classifier that has some hidden layers (experiment to discover how many you need to have a good classifier, do not attempt more than 4 hidden layers).
6. Use CrossEntropyLoss and the Adam optimizer to train your Neural network.
7. Provide the loss over your epochs (use 200)
8. Tell me the accuracy of your model!
Please use the documentation, ChatGPT and torch tutorials to give you a better understanding of the material. We cannot cover everything in class due to our time constraints. Therefore, some things in this assignment we will not have explicitly covered in class. If these resources are not writing code for you or replacing your work, I have no issue with you using them.

Upload your tutorial and your apple quality solution in a zip file. Please also include the output of the shell when you execute each assignment. The execution will demonstrate your correct code.