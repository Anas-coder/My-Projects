**Its an approach towards Deep Learning where I have learned how to set up a 2 layer neural network. How to use the correct optimizer in the correct layers**

## Part 1 - Data Preprocessing
-Loading the Data -Importing the relevant libraries -Separation of input and output and storing in X and Y -Created dummy variables for two columns
-Concatenated the Data Frames
-Dropped Unnecessary columns -Splitting the Data into train and test and applied standard scaling.

## Part 2-Now let's make the ANN!
-Importing the Keras libraries and packages -Initializing the ANN 
-Adding the input layer and the first hidden layer -I have used kernel_initializer = 'he_uniform', activation='relu' 
-Adding the second hidden layer -In the second layer I have used the same kernel_initializer = 'he_uniform', activation='relu' (In 1st and second layers I have used kernel_initializer = 'he_uniform', activation='relu' to avoid vanishing gradient decent) 
-Adding the output layer -I output layer I have used kernel_initializer = 'glorot_uniform', activation = 'sigmoid' -Compiling the ANN -Fitting the ANN to the Training set

## Part 3 - Making the predictions and evaluating the model

-Making the Confusion Matrix -Calculated the Accuracy which is 85% on test data
