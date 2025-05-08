# 2025_ia651_bartiromo

Ethan Bartiromo 03/25/2025-05/07/2025
IA651 taught by Professor Michael Gilbert
Stock Market Open/Close Prediction on 5 of the top tech stocks.
Necessary documents to read:
README.md
Ethan_Bartiromo_Final.ipynb
Comments.txt


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
* Completed the XGBoost analysis, and found the best model thus far again - 04/26/2025
* Started Seasonal Decompose model analysis - 04/26/2025
* Completed Seasonal Decompose (Which ended up just being Exponential Smooting) which did VERY poorly - 05/01/2025
* Uploaded everything into a final pynotebook - 05/07/2025
* Noticed that loading a keras model with a lambda layer does not work properly - 05/07/2025
* Uploaded the Google CoLab pynotebook as supplementary details - 05/07/2025
* Created a bar chart showing the mean squared error of each model - 05/07/2025
* Fixed MSE calculation for the Exponential Smoothing - 05/07/2025
* Created Comments.txt - 05/07/2025
* Added file descriptions below - 05/07/2025
* Added Title sequence up top - 05/07/2025
* Committed and pushed to GitHub, zipped, and turned in to Moodle - 05/07/2025


Files included in Folder:
* AAPL.csv - Dataset 1/5
* GOOGL.csv - Dataset 2/5
* META.csv - Dataset 3/5
* NVDA.csv - Dataset 4/5
* TSLA.csv - Dataset 5/5
* .gitignore - Python Notebook Github command
* my_model_1.keras - Model 1/6 (Corrupted)
* model_2.pkl - Model 2/6
* model_3.pkl - Model 3/6
* model_4.pkl - Model 4/6
* model_5.pkl - Model 5/6 (Model 6 is not saved as it's own file)
* Ethan_Bartiromo.ipynb - Original PyNotebook (Where all of the original coding and editing takes place)
* AML_COLAB.ipynb - Google CoLab supplimentary PyNotebook (Where some of the excess model training took place)
* Ethan_Bartiromo_Final.ipynb - The final product showing the graph of MSEs for each of the 6 models
* Comments.txt - A copy of the comments made on model design throughout the process of the project
* README.md - The readme consisting of all of this documentation



THANK YOU FOR THE WONDERFUL CLASS THIS SEMESTER!