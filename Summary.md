# Homework 14 Summary

In this exercise, I built a single LSTM model and tested it for predicting Bitcoin closing prices using either the FNG value or the previous closing prices as inputs.  The model used three layers of LSTM, three layers of dropouts, and a dense layer with sigmoid activation.  

The FNG model was able to predict many of the upturns in closing price, but missed almost all of the downturns.  The closing price model was significantly more accurate, predicting both the up and downturns.
