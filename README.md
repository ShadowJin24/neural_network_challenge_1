# neural_network_challenge_1

Part 1: Prepare the data for use on a neural network model
Using Pandas and scikit-learn’s StandardScaler(), preprocess the dataset to compile and evaluate the neural network model later.

Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csvLinks to an external site. into a Pandas DataFrame. Review the DataFrame, looking for columns that define your features and target variables.

Create the features (X) and target (y) datasets. The target dataset defined by the “credit_ranking” column. The remaining columns should define the features dataset.

Split the features and target sets into training and testing datasets.

Use scikit-learn's StandardScaler to scale the features data.

Part 2: Compile and Evaluate a Model Using a Neural Network
Use TensorFlow to design a deep neural network model. This model should use the dataset’s features to predict the credit quality of a student based on the features in the dataset. Consider the number of inputs before determining the number of layers that the model will contain or the number of neurons on each layer. Then, compile and fit the model. Finally, evaluate the model to calculate its loss and accuracy.

Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using TensorFlow’s Keras.

Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

Evaluate the model using the test data to determine the model’s loss and accuracy.

Save and export the model to a keras file, and name the file student_loans.keras.


Part 3: Predict loan repayment success by using the neural network model
Use the model saved in the previous section to make predictions on the reserved testing data.

Reload the saved model.

Make predictions on the testing data, saving them to a DataFrame and rounding the predictions to binary values.

Generate a classification report with the predictions and testing data.

Part 4: Discuss creating a recommendation system for student loans
Briefly answer the following questions in the space provided:

Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.
