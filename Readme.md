# README

### Overview
This is a personal solution attemp for the 'Predict Future Sales' Kaggle competition. 
The project itself was developed entirely on Google Colab, aiming to use GPU power while training LightGBM and XGBoost models, that's the reason you'll notice some comented specific Colab's commands (the original ones used). Nevertheless, I've modified the code so it can run in a local machine.


### Structure
This repo is made of 3 folders:
* Data:
    > Contains all the data files used in the project:<br>
        >> Given files<br>
        >> Translated files (from Russian to English)<br>
        >> Preprocessed files<br>
* Preprocessing
    > Contains Translation, EDA and Preprocessing files
* Modeling
    > Contains LightGBM, XGBoost and Stacking (on Linear Regression) files and serialized models
<br><br>
Beware that the file df_preprocessed.pkl is not in the repo as it was +500MB, to retrain the models you'll need to generate it running the Preprocessing file

