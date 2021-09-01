# stock_price_prediction
To build a model that can predict stock prices (using Deep Learning)
Language : Python3

Frameworks : Tensorflow2 , Keras , Pandas , Numpy , Matplotlib

Description : We have used a **stacked multi layered LSTM** to predict the stock price of google and facebook.

Loss Function = **Mean_Squared_Error**

Optimizer = **Adam**

Dataset - Historical data of Google and Facebook stock Prices are taken from Yahoo Finance

Both the models are almost similar except for number of LSTM units in each layer

Google Dataset : GOOG (2).csv 
Trained for 30 epochs
Model Architecture :
![image](https://user-images.githubusercontent.com/59412269/131734947-2934e601-cd5a-43b7-962d-ac9066722f8c.png)

Output Waveform of predicted and actual stock prices over time :
![image](https://user-images.githubusercontent.com/59412269/131735032-9b3ec8b0-dd41-4e0e-9a7d-dc58cc6a7a08.png)

Facebook Dataset : FB.csv
Trained for 50 epochs
Model Architecture :
![image](https://user-images.githubusercontent.com/59412269/131735134-433cc89c-1e16-4b16-b70a-5c5722872bd9.png)

Output Waveform of predicted and actual stock prices over time :
![image](https://user-images.githubusercontent.com/59412269/131735268-7ee1e084-ef66-40f4-b849-d2682dd3b3a2.png)

All the above files are uploaded along with code for the model

As we can observe in the graph the predicted values are very near to real values. 
And in both models loss has been reduced to almost 0.001

From output graphs we can infer that the models are working as expected.
