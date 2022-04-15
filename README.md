# Predicting House Prices with Machine Learning

  This repository contains code for team 6's IDS 705 final project. The goal of the project is to predict house prices using housing data for [Georgia](https://www.kaggle.com/datasets/yellowj4acket/real-estate-georgia) and [California](https://www.kaggle.com/datasets/yellowj4acket/real-estate-california). All of the intial data is in the Data folder, which is all you need to run the repo. While all of our scratch work and draft files are in the the Scratch folder. All of the final versions of the files, needed to run the analysis, are in the Code folder and the models are in the Model folder. 

  The files within the anlaysis are numerically labeled and should be run in order. To start you first need to run the "10_EDA&Cleaning2" followed by "20_Preprocessing3" to generate the needed data, which will be saved to your Data folder. Once those files are run we were interested in testing out different possible models. The different models are in seperate files that are each named according to the model type run in the file. The final model used was a light gbm model and the model is trained and validated on different groups of data: by state and home type. The final models are validated in the according files: "51_Validate_all" (model for all of the data), "52_Validating_On_California_Model" (CA and GA on CA model), and "53_Validating_On_Georgia_Model" (CA and GA on GA model).


## Contributors
| Name | Reference |
|----|----|
|Minjung Lee| [GitHub Profile](https://github.com/minjung0)|
|Rachel Richards|[GitHub Profile](https://github.com/rjrichards27)|
|Robert Wan| [GitHub Profile](https://github.com/rw417)|
|Himangshu Raj Bhantana | [GitHub Profile](https://github.com/hb173)|
