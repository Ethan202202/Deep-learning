# Deep-learning
###  This assignment will use deep learning recurrent neural networks to model bitcoin closing prices.
## Step 1: Prepare the data for training and testing
The first model is Fear and Greed model. I use the FNG values to try and predict the closing price.
The second model is closing price model, I use previous closing prices to try and predict the next closing price.
Each model has 70% of the data for training and 30% of the data for testing.
## Step 2: Build and train custom LSTM RNNs
Using the same parameters and training steps for each model to compare each model accurately.
## Step 3: Evaluate the performance of each model
## Result:
### The predictor using closing prices has the lowest loss which is 0.0146 .
### The model using past closing prices tracks the actual values better.
### For the model using past closing prices, windows size 6 has the best performance.
## Here are the mean standard error for each window: 
### 1 :0.0721718
### 2 :0.0411839
### 3 :0.0158718
### 4 :0.0092139
### 5 :0.0083639
### 6 :0.0080551
### 7 :0.0084306
### 8 :0.0095089
### 9 :0.0108110
### 10:0.0125179
## For the model using fear and greed index, windows size 10 has the best performance.
## Here are the mean standard error for each window:
### 1 :0.1041931
### 2 :0.1013033
### 3 :0.0993965
### 4 :0.0984315
### 5 :0.0975406
### 6 :0.0968821
### 7 :0.0962102
### 8 :0.0955662
### 9 :0.0946289
### 10:0.0942297
