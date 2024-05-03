# BitCoin Transactions: Ransom-Ware Detection

## Project Overview

The purpose behind this project was to compare the differences in performance of classical classification Machine learning algorithims such as KNN, and Logistic Regression, to that of its more advanced counterparts. Additionally, the implementation of the TabTransformer architecture, which is a data modeling architecture for supervised & unsupervised learning built on self-attention based Transformers. The intent was to identify which model could perform the best in detecting if a BitCoin transaction was an act of ransomware or not based on many different variables. 

## Models Used

- Decision Tree Classifier: A tree structure method emplyoing IF ... THEN statements to model the data & predict future values.

- K-Nearest Neighbor Classifier (KNN): A non-parametric method that classifies cases based on their similarity to other instances.

- Logistic Regression: A statistical model that estimates probabilities using a logistic function.

- Gaussian Naive Bayes: A statistical model that esitmates probabilites assuming the features are pair-wise conditionally independent & maintain a normal distribution for the continuous variables.

- Support Vector Machine: A complex model that develops a linear seperation between the classification classes & localizes in a manner that the largest margin seperates the classes under consideration.

- Linear Support Vector Machine: Similar to the simple SVM, but performs faster for linear cases & is more robust in the model performance loss.

- TabTransformer: A self-attention based Transformer that takes a split input of categorical & numerical variables, then concatenates them before pushing them through a dense perceptron layer.

- AutoGluon Tabular Machine Learning package: A robust off the shelf package that can test many Machine Learning Models easily & quickly. Added more as an interesting thing to note rather than investigating.

## Files

`COE 379 Final Report`: Full write up explanation of the project, with further detailed analysis.

`Bitcoin_models.ipynb`: The Jupyter notebook that shows the step-by-step data processing, visualization, model fitting, and model analysis.

`Project Proposal`: Initial proposal for our project & ambition behind it.
