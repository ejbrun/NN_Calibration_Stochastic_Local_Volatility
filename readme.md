## Model Calibration with deep networks

Eric Brunner, eric.brunner@uranus.uni-freiburg.de

We try to calibrate stochastic local volatility models by learning the local volatility function by means of a neural network. The folder heston_slv_calibration contains a calibration of both the stochastic and the local volatility part by means of neural networks. The slv_sabr_calibration folder contains some numerical tests on the calibration of the SABR-model where also hedges are learned via a neural network.

Remarks:
The code works with tensorflow 1.15 and keras 2.3.1.. Note, that, for some reason I do not understand, the code does not work in tensorflow 2.0 or newer.



