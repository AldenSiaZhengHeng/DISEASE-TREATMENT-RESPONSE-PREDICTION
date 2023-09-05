Machine_Learning_CW2

############
Instruction
###########
1. Please ensure the file path of the dataset is correct before run the code.
2. Please ensure the python environment (numpy, tensorflow etc) is set.
3. All of the section have a comment to explain their function.
4. The codes are built and running in jupyter lab notebook.
5. There are two model to be used to compare the result.
6. Root mean square error and mean absolute error will be determined with 5-fold cross validation.
7. Classification Accuracy will be determine with 5-fold cross validation.
8. There will be two folder which are finaltest_file and development_file folder

#####################
finaltest_file folder
#####################
1. There will be two files which are FinalTestPCR and FinalTestRFS to predict the PCR and RFS of the test datasets.
2. In each file the saved model will be loaded and the .csv file that contain the best feature name will be read.
3. The predicted result will then store into the csv file named as FinalTestPCR_result.csv or FinalTestRFS_result.csv

#####################
finaltest_file folder
#####################
1. This folder contain 8 file to implement and compare the best model for regression and classification tasks.
2. The KNN Regressor with SBS and  MLP with linearSVC file will save their model trained and feature selected name as these two models are the best model.
3. Please drag the model saved in "sav" format and feature selected csv file into finaltest_file folder for testing if re-run the program or re-train the model