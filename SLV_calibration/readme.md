## Calibration of stochastic local volatility model

Eric Brunner, eric.brunner@uranus.uni-freiburg.de

The notebook SVL-valib-stochastic contains the calibration of the stochastic part (Heston model) of the SLV model. The calibrated Heston-parameters are imported in SLV-calib-local, in which the local volatility is calibrated by means of a deep neural network.

Remarks:
The code works with tensorflow 1.15 and keras 2.3.1.. Note, that, for some reason I do not understand, the code does not work in tensorflow 2.0 or newer.



