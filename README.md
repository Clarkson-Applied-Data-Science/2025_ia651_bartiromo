# 2025_ia651_bartiromo
* Created the GitHub and started project - 03/25/2025
* Found and uploaded datasets to work on - 03/25/2025
* Had first project meeting - 03/26/2025
* Fixed issues with GitHub organization - 03/26/2025
* Pushed all datasets and fixes to the new GitHub repo - 03/26/2025
* Imported all necessary libraries - 04/15/2025
* Combined all datasets into one Dataframe - 04/15/2025
* Created helper functions to create Tensorflow models - 04/15/2025
* Tried to implement Tensorflow models as scikitlearn subclasses for GridSearchCV - 04/15/2025
* Ended up making it easier by implementing my own grid search and no subclass nonsense - 04/17/2025
* Went to office hours and fixed all bugs in code for making, fitting, predicting, and evaluating the model - 04/18/2025
* Converted the model from 25 input variables and 100 output variables to 2500 input variables and 100 output variables - 04/18/2025
* Optimized code to run what was originally a double for loop to train test split into a single for loop - 04/18/2025
* Started running a grid search with 6 different train test splits and 8 different neuron patterns - 04/18/2025
* The grid search finally stopped running, and I plan to leave some extraneous code to have it as a view - 04/19/2025
* Added comments and extra markdown - 04/19/2025
* Pushed and committed to GitHub now - 04/19/2025
* Implemented early stopping, gave a fixed number of epochs, optimizer, and random seed for repeatability - 04/19/2025
* Corrected early stopping with loss instead of validation loss - 04/19/2025
* Optimized the grid search for a specific train test split, and found the best hyper parameters - 04/19/2025
* Completed the RNN with the best loss, which even with the same seed does not give the same results - 04/19/2025
* Started working with XGBoost algorithms - 04/21/2025
* Noticed that one of the most naive models of XGBoost had better loss than any of the RNNs - 04/21/2025
* Started using Google Colab to allocate server resources instead of my local CPU - 04/21/2025
* Created and ran a grid search for XGBoost which took over 4 hours and 48 minutes to run
* Saved the pickl files of the XGBoost models - 04/21/2025
* Found out that Google Colab deletes all files after runtime ends, so the models got deleted - 04/21/2025
* Fit the XGBoost models with the same hyper parameters as the best 3 chosen before - 04/21/2025
* Started transforming data with MinMaxScaler in order to fit on percentages of change between min and max instead of $ value - 04/22/2025
* Had issues with the MinMaxScaler, made a plan to observe and fix - 04/22/2025
* Updated README and uploaded pickl files to project folder as well as pushing and committing to GitHub - 04/22/2025
