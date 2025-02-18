Jan. 16, 2025

Due to version incompatibility issue of Scikit-learn and eXtreme Gradient Boosting library, it was necessary to use scikit-learn 1.5, downgrade from 1.6 which was used primarily in this folder.

Hence, the updated and valid results and models are found inside the XGB_only folder, where most of the modelling was repeated but this time using scikit-learn 1.5.

However, due to time constraints, the hyperparameter tuning for Random Forest, Light Gradient Boosting, and Catboost were not repeated in the new folder. An assumption is made that the parameter values were not affected by the change (some examples were taken to compare).

Hence, the CV table to be used for the model reports should be taken from this folder.