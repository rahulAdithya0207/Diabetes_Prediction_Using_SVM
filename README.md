# Diabetes_Prediction_Using_SVM

1.Importing all the dependencies.
2.Loading the dataset. 
3.Compute the statistical measures like mean , median and mode for the dataset. To get the understanding of how the data is distributed and to identify the central tendencies or common values which can help in summarising the pattern.
4.Another important aspect is standardising the data, which is really necesary to bring all the features to a commonn scale, ensuring that no feature dominates due to its range.
5.Train_Test_split function splits the dataset into training and testing data. Here 80% of the data is used for training the model and the reamining 20% for testing the model. Also ensure equal composition of the 0 and 1 labels in both the training and the testing data , for that we inlcude stratify = Y into the argument.
