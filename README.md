# Project 1

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project 1 is due Tuesday, October 11 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/459156/assignments/5393751) in the Canvas assignment.

## Dataset - Supermarket Sales

The dataset you will be working with has been pushed to this repository under the name "supermarket_sales.csv".

## Files contained

1. training.ipynb ---- code used for training the datasets.
2. test.ipynb ---- code used for testing the datasets.
3. supermarket_sales.csv ---- original dataset.
4. data.csv ---- dataset only with modification in 'Date' and 'Time'.
5. train_prepared.csv ---- training dataset with scaling in numerical attributes and encoding in categorial attributes, can use for training directly
6. test_prepared.csv ---- test dataset with scaling in numerical attributes and encoding in categorial attributes, can use for test directly
7. Project 1 - Building & Evaluating ML Algorithms.ipynb ---- description of project 1
8. Model ---- contain all models generated from the training.ipynb.
9. Problem 6 data ---- contain X_train, X_test, t_train, t_test dataset for problem 6
10. Project_1_report.docx ---- report in docx form
11. Project_1_report.pdf ---- report in pdf form
12. training.pdf ---- pdf form of training.ipynb
13. test.pdf ---- pdf form of test.ipynb
14. README.md ---- this file.

## How to use 

Training: Training code do not need any parameters to input. It generates totally 11 models in file Model, and these models will be use in test code.    
Test: Test code has already loaded the datasets in preprocessed state, and all models have been loaded too. Except running all codes, you do not need any operation in Jupyter.