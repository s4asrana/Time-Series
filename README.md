# Time-Series using LSTM

The task here is to do the time series analysis of the climate data, or specifically the temperature column, i.e, to build a model that tries to predict the temperature based on the past temperature data.
The dataset used is from Kaggle and has around 420000 rows and 15 columns, which is quite big.

For this project Long short term memory neural networks are used, which are an updated version of recurrent neural networks(RNNs). RNNs are special architectures that take into account temporal information, which is extremely important for natural language processing as well as many time series tasks as in both these tasks there is a serial dependnecy or auto-correaltion which LSTMs can capture really well.

RNNs suffer from short-term memory problem and because of this LSTM’s were created. They have internal mechanisms called gates that can regulate the flow of information. By doing that, it can pass relevant information down the long chain of sequences to make predictions.

WorkFlow of the task:

1: Data reading using pandas library.

2: Data preprocessing and cleaning like finding and handling null and missing values.

3: Transforming data, i.e, reducing size of the data and converting it into a suitable form so that it can be fed to the deep learning model and doing train-test split.

4: Creating deep learning model and fitting it on the training data.

5:  Evaluatig the results by plotting the real data and the predicted data. 



