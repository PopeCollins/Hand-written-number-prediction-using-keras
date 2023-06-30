# Hand-written-number-prediction-using-keras
Prediction of handwritten numbers using Keras

MMIST dataset from the Keras library was used in this project. I split the data into training and testing parts for the model prediction. 

I normalize the pixel value of the train and test data using the keras normalize function basically this is to speed up the model learning. 
After I build a sequential model and added some layers( Flatten, Dense Layer using Relu as activation functions, and Dense Layer with Softmax activation functions).

Further, I compiled the model using ADAM optimizer, Then the model was fitted using the X_train and y_train with number of epochs as 3.

The actual calculated loss and accuracy were gotten to be 2% loss and 97% accuracy.
Then the model was saved for predictions. I predicted all the data of the x_test and printed the predictions in a multidimensional matrix. 
Using a numpy array to check the particular argument each of the images of the  x_text was passed into the array and the prediction outcome was right.

