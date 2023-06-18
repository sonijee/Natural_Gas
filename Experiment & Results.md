In this study, LSTM algorithm is applied on the created
dataset and experiments are performed to find the best results.
All the tests are evaluated and executed with use of Python
and the libraries Tensorflow, SciKit-Learn, Pandas, Numpy,
Matplotlib and Seaborn.


For the implementation, comparison of dropout rate, timesteps
input, batch size has been evaluated as shown in Tabel II, III
and IV. 
![table2](https://github.com/sonijee/Predictions/assets/136623761/60a3bba0-cdb2-44e8-be22-9ad93c407786)

Table II shows the variations in results as dropout
rate changes for 20 units & 40 units in hidden layer 1 &
2 respectively with batch size 1 and 24 previous datapoints
as input for 1 output unit. The performance of the model is
increasing as we are reducing the dropout rate.

![table3](https://github.com/sonijee/Predictions/assets/136623761/1005a412-1805-4020-a08d-e9aedb9d1703)

Table III exhibits the variations in results as timesteps for
input layer changes for 20 units & 40 units in hidden layer 1
& 2 respectively with batch size 1 and dropout rate set to be
0. The optimal results are produced when previous 24 months
values are considered for input.

![table4](https://github.com/sonijee/Predictions/assets/136623761/4453bb7b-e1b2-41f8-b21f-d4854b2bb184)

Table IV demonstrates the variations in results as batch
size changes for 20 units & 40 units in hidden layer 1 &
2 respectively with 24 units in input layer and dropout rate
set to be 0. Smaller batch size results into better training
and forecasting. 

![table5](https://github.com/sonijee/Predictions/assets/136623761/16257151-9704-4617-81b2-165854b2d9fb)

Finally LSTM model is compared with the existing methods used in monthly forecasting of natural gas
consumption. In multiple linear regression (MLR) method,
the model equation founds to be
Natural gas consumption = -0.0639 Price + -0.4797
Temperature + 0.1180 Population + 0.3588Export + 0.460(Constant).
Temperature shows the higher impact (β = −0.4797 )on
natural gas consumption. Results in Table V shows that LSTM
slightly outperform the SVR method which uses cubic polynomial kernel function with insensitive coefficient ϵ = 0.001 and
regularization parameter C = 1.
![r1](https://github.com/sonijee/Predictions/assets/136623761/1a7b38c9-a31c-4517-9b6a-fdce88151971)
Figure shows forecasting  of natural gas consumption using LSTM.

