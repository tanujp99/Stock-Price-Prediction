# Stock-Price-Prediction

In this mini project, application of Time series regression  is carried out using Python(computer language for coding), FBProphet and Streamlit that caters the requirement sufficiently. Streamlit is an open-source app framework for Machine Learning and Data Science teams. It has Python libraries that makes it easy to create and share custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. FBProphet uses time as a regressor and tries to fit several linear and nonlinear functions of time as components. At its core, the Prophet procedure is an additive regression model. A piecewise linear or logistic growth curve trend. Prophet automatically detects changes in trends by selecting changepoints from the data.

### Pickle:
Python pickle module is used for serializing and de-serializing a Python object structure. Any object in Python can be pickled so that it can be saved on disk. What pickle does is that it “serializes” the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script.

### Recurrent Neural Network
We have used RNN for the past analysis of our target stock. So we have only worked with the Target Stock Feature file . Now, here we use LSTM layers that work on RNN principles but work on a gated approach.The LSTM helps the RNN to keep the memory over a long period of time, solving the vanishing and exploding gradient problems.

### LSTM
Long Short Term Memory
3 Gates: Forget, Input, Output. 
Forget gate discard redundant/Irrelevant data.
Capable of adding and removing features from the model as it learns dynamically, type of RNN

LTP: Last trade Price 
CMP: Current Market Price
