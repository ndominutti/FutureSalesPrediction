# README

### Overview
This is a personal solution attemp for the Predict Future Sales' Kaggle competition. <br>
The whole project was developed entirely on Google Colab, aiming to use GPU power while training LightGBM and XGBoost models. Nevertheless, every file but the models training ones had been modified to work exactly as they are on a local computer.


### Structure
This repo is made of 3 folders:
* Data:
    > Contains all the data files used in the project:<br>
        >> Given files<br>
        >> Translated files (from Russian to English)<br>
        >> Preprocessed files
* Preprocessing
    > Contains Translation, EDA and Preprocessing files
* Modeling
    > Contains LightGBM, XGBoost and Stacking (on Linear Regression) files and serialized models

