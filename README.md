# Predicting if a Song will be a Billboard Hit or Not?
Rice DSCI 303 Fall 2020 project

By: Josh Kowal, Kunal Rai

# The Project 

The main goal of this project is to develop a model(s) that can accurately predict whether a song will be a Billboard Top 100 hit or not based on the audio and lyrical features of the song. 


# To use this Repository

**Ensure that data folder is inside the project and install the libraries using the requirements.txt**


## Installation

`git clone https://github.com/kunalrye/spotify_hits.git` \
`pip3 install -r requirements.txt` 

## Running code 
To run our code and reproduce the results shown in the report, you can run each of the ipynb files (``Modeling_.ipynb`` & ``Modelling.ipynb``) which contain all the models discussed in our report. The dataset we created is already provided in the data folder. To create the subset used for training (which is in the data folder already), run ``CreateFinalSubset.ipynb``.


# In this directory

* ``requirements.txt`` - Packages required to run this repository
* ``data`` - Directory containing the main data files for this project
* ``archived`` - Directory containing old .ipynb files that are not reproducible or essential to project
* ``CreateFinalSubset.ipynb`` - Notebook containing the code to create the final subset from the final dataset
* ``Modeling.ipynb`` - Notebook containing Logistic Regression, Neural Network, Gradient Boosting Classifier, and XGboost models
* ``Modelling.ipynb`` - Notebook containing Random Forest, SVM, and another Gradient Boosting Classifier
* ``303_Final_Report_2.pdf`` - Final report for this project detailing our data science pipeline and project results



