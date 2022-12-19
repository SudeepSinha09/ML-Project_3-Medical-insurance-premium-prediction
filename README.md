# ML-Project_3-Medical-insurance-premium-prediction
### Data Details 

  Kaggle - https://www.kaggle.com/datasets/mirichoi0218/insurance?select=insurance.csv
  Colab Notebook - https://colab.research.google.com/drive/1w0fnpjcNyc2Oee151ugULerTwWJcYVv4?usp=sharing
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_3-Medical-insurance-premium-prediction/blob/main/Medical%20insurance%20premium%20prediction.ipynb

## Description

Machine Learning with R by Brett Lantz is a book that provides an introduction to machine learning using R. As far as I can tell, Packt Publishing does not make its datasets available online unless you buy the book and create a user account which can be a problem if you are checking the book out from the library or borrowing the book from a friend. All of these datasets are in the public domain but simply needed some cleaning up and recoding to match the format in the book.

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/208367286-dd672749-bbe4-430c-a551-ebac63d93a6e.png)

![image](https://user-images.githubusercontent.com/93086122/208367322-9a21fc38-3cf8-4f39-9717-23409a004753.png)

### Columns

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance

## Project Brief

As part of this project, I cleaned the data, after which I train-tested the data, and then I made models using the train data.

For the given situation, there are three possible models, namely (i) Multiple linear regression (ii) Random Forest (iii) XGBoost

In order to determine the accuracy of each model, I made predictions based on the train data before making the models, i.e. predicting the models with the train data.

Using these parameters, we found that the accuracy, recall, precision, and f1 scores of both Multiple linear regression models and random forest models or XGBoost models are approximately the same, so we cannot predict the best model based on these parameters.

so now we are checking for the Cross Validation test

Result - Compairinng r squre values for all the 3 models we can conclude that best model is XGBoost

##### The model selected - Logistic regression

###### [imp] In genral we do randamosesearchCV or GridsearchCV to find the best fitted model but here as we hav ecompaired the models using r squre test hance we are not goin to perform CVs here
