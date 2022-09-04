# Stack Overflow Data, a Further Analysis
Project #1 for the Udacity Nanodegree Program for Data Science.

## Table of Contents
- [Installation](#installation)
- [Project Motivation](#project-motivation)
- [Files Description](#files-description)
- [Results](#results)
- [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

## Installation
The code was written with a Jupyter notebook from a local Anaconda environment, and it should have no issues in running a version of Python 3.* or greater.
NB: for compatibility issues, the command `LinearRegression(normalize = True)` has been substituted with the function `StandardScaler()`.

## Project Motivation
This project aims at analysing further the Stack Overflow Data from the 2017 survey. 
In particular, the project focuses on:
1. Is it possible to create a model that foresee the Salary of an individual based only on the categorical variables who have not any missing values in the Dataset?
2. Is it possible to reduce the dimensionality of our problem (predicting salaries based on other factors), and is there a relation between dimensionality and number of features used?
3. Is the Expected Salary a more predictable indicator than the Salary?

## Files Description
The projects constitute of four files:
1. `StackOverflowUdacityProject1.ipynb` file: where the code and results of the analyses lie;
2. `README.md`: this very file;
3. `survey_results_public.csv`: results of the Stack Overflow 2017 survey, as for original Udacity project;
4. `survey_results_schema.csv`: explanation of the variables and answers of the survey (file not used for this project).

## Results
The findings of the analyses can be found in the `.ipynb` file, as [here](https://medium.com/@corrado.campodonico/data-science-the-devil-lies-in-details-e6598fa1d221).

## Licensing, Authors, Acknowledgements
Stack Overflow data belongs to Kaggle, and it can be found [here]([https://medium.com/@corrado.campodonico/is-it-so-easy-to-guess-a-developers-salary-e6598fa1d221](https://www.kaggle.com/datasets/stackoverflow/so-survey-2017)).
The code is free for use.
