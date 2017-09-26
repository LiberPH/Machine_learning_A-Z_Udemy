# Machine_learning_A-Z_Udemy
Code and information of the machine learning course :D

## A little of history

- From the dawn of time to 2005, humans had generated 130 exabytes
- From the dawn of time to 2010, humans had genrated 1,200 exabytes
- In 2015, humans had generated 7900 exabytes
- In 2020 it is expected that humans will have generated 40,900 exabytes

## 6 Extra about instructors and stuff

- **Super datascience podcast O.o**: https://www.superdatascience.com/sds-002-machine-learning-recommender-systems-and-the-future-of-data-with-hadelin-de-ponteves/
- **What is Machine Learning**: 
	Can be used for: 
	- Predictions
	- Discover logic in a field (clustering and segmentation)
	- Interactive machine learning (choose best adds at the right moment, reinforcement learning)
	- Deep learning.
	- Big science that englobes many fields (AI can be defined the same way as artificial intelligence). Machine "learns" how to do stuff by itsels.
	- A data scientist is also a macine learning scientist

# Topics in machine learning
	- **Regressions**: Predict a real value
	- **Classifications**: Predict a category
	- **Clustering**:
	- **Association rule learning:** associations and logic in the business to create value
	- **Reinforcement learning**
	- **Deep learning:** Facial, voice recognition (more python than R).
	- **Natural language processing!**: Text, analyzing feelings.
	- **Dimensional antireduction:** Get the important variables in the data.

# Data pre-processing **(without it your machine learning model won't work properly)**.

Finding the data for this course: https://www.superdatascience.com/machine-learning/

## **IMPORTANT: Differentiate between dependent and independent variables**
In any machine learning model we are going to use independent variables to predict a dependent variable

## **Importing libraries**

### Python

Main libraries to be used:

- numpy as np: includes mathematical tools
- matplotlib.pyplot as plt: make nice plots
- pandas as pd: import and manage datasets

## Importing data sets

The first data set to work with is:

| Country | Age | Salary | Purchased | 
|---------|-----|--------|-----------| 
| France  | 44  | 72000  | No        | 
| Spain   | 27  | 48000  | Yes       | 
| Germany | 30  | 54000  | No        | 
| Spain   | 38  | 61000  | No        | 
| Germany | 40  |        | Yes       | 
| France  | 35  | 58000  | Yes       | 
| Spain   |     | 52000  | No        | 
| France  | 48  | 79000  | Yes       | 
| Germany | 50  | 83000  | No        | 
| France  | 37  | 67000  | Yes       | 

Where: country, age and salary are dependent variables


### Python

```python

#Data Preprocessing

## Importing the libraries
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd

# Importing the dataset
dataset = pd.read_csv('Data.csv')

```


***Important for machine learning:*** Discriminate between the matrix of features and the dependent variable vector.

***Difference between python and R:***Arrays in R start in 1, while in pyton they start in 0.

