# Predicting House Prices with Machine Learning

This repository contains code for team 6's IDS 705 final project. The goal of the project is to predict house prices using housing data for [Georgia](https://www.kaggle.com/datasets/yellowj4acket/real-estate-georgia) and [California](https://www.kaggle.com/datasets/yellowj4acket/real-estate-california). All of the intial data is in the Data folder, which is all you need to run the repo. While all of our scratch work and draft files are in the the Scratch folder. All of the final versions of the files, needed to run the analysis, are in the `Code/` folder and the models are in the `models/` folder. 

The files within the anlaysis are numerically labeled and should be run in order.
- To start you first need to run `Code/10_EDA&cleaning.ipynb` followed by `Code/20_Preprocessing.ipynb` to generate the needed data, which will be saved to your Data folder. Once those files are run we were interested in testing out different possible models.
- The team tried fitting different types of models to compare performance. The different models are in seperate notebook files whose names all start with "3x_" in the `Code/` folder. The files are each named according to the model type.
- The final model used was a LightGBM model. The model training code can be found in `Code/41_train_final_models.ipynb`. We trained 3 models: a model with training data from both states, and a model for with training data for each state.
- Trained models are saved in the `models/` folder so that you don't have to retrain the models.
- The final models are tested using test data in the following files: `Code/51_Validate_All_Data_Model.ipynb`, `Code/52_Validating_On_California_Model.ipynb`, and `Code/53_Validating_On_Georgia_Model.ipynb`.


## Contributors
| Name | Reference |
|----|----|
|Minjung Lee| [GitHub Profile](https://github.com/minjung0)|
|Rachel Richards|[GitHub Profile](https://github.com/rjrichards27)|
|Robert Wan| [GitHub Profile](https://github.com/rw417)|
|Himangshu Raj Bhantana | [GitHub Profile](https://github.com/hb173)|
