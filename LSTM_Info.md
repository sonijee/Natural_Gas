LSTM is a type of recurrent neural network (RNN), which is getting used to solve the difficulty in learning. The  RNNs are not able to learn very long time dependent information. In the cases like long dependencies, where space between
the important information and the output place is small, RNNs do not perform well with such long dependencies. 
The scaled data has been feed to the LSTM network for training.
Activation function used in hidden layer is ”Rectified Linear Unit (RELU)”. Adam Optimizer was used to optimize the weights and learning rate and improve the accuracy of the model. Mean squared error was computed to check the error loss for each 50 epoch used. Batch size, dropout rate, timesteps for input were tuned to find the lesser error.
For the LSTM neural network implementation, as data needs to be given in 3D tensor, we convert the data into the shape (195,24,5) for training and (12,24,5) for test data. For each row, we have its previous 24 rows with 5 attributes as input shape. In between input and output layer, 2 lstm layers are used for training the model with 20 and 40 neurons respectively as shown in Figure

![loop](https://github.com/sonijee/Predictions/assets/136623761/ad40c8dc-8426-41b6-8bef-66e392fa7566)

