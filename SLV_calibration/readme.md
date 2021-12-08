## Calibration of stochastic local volatility model via neural networks

Eric Brunner, eric.brunner@uranus.uni-freiburg.de

The notebook SVL-calib-stochastic.ipynb contains the calibration of the stochastic part (Heston model) of the SLV model. The calibrated Heston-parameters are imported in SLV-calib-local.ipynb, in which the local volatility is calibrated by means of a deep neural network. A more detailed project description and discussion of the calibration results are given in deep_calibration_SLV_model.pdf.

Remarks:
The code works with tensorflow 1.15 and keras 2.3.1.. Note, that, for some reason I do not understand, the code does not work in tensorflow 2.0 or newer.
