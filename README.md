# Logistic-regression--item-purchaced-or-not



Predicting Product Purchases with Logistic Regression


Description

This project uses logistic regression to predict whether or not a customer will purchase a product based on their age and gender. The data used in this project comes from the Social Network Ads dataset, which contains information on whether or not a customer purchased a product based on their age, gender, and estimated salary.


Technologies Used


Python 3.11

pandas 1.3.4

NumPy 1.21.4

seaborn 0.11.2

scikit-learn 1.1.1


Installation

To run this project, you will need to have Python 3.11 installed. You can download Python from the official website: https://www.python.org/downloads/


Once you have Python installed, you can install the necessary libraries by running the following command in your terminal:


Copy code

                      pip install pandas numpy seaborn scikit-learn
                      
                      
Usage

To use this project, you can run the code in a Jupyter notebook or in a Python script. The code reads in the data from the Social Network Ads dataset, preprocesses the data by encoding the gender column using LabelEncoder, splits the data into training and testing sets using train_test_split, fits a logistic regression model to the training data, and then makes predictions on the testing data.


To make a prediction for a specific age and gender, you can change the value of the value variable and run the model.predict([[value]]) line of code.



License


This project is licensed under the MIT License - see the LICENSE file for details.
