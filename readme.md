## Calibration of stochastic local volatility model via neural networks

### Dependencies:
- Tensorflow 1.15
- Keras 2.3.1

We calibrate stochastic local volatility (SLV)) models by an approach based on neural networks. In the first step, the stochastic volatility model (Heston model) is calibrated by learning the map from Heston parameters to volatility surface by means of a neural network. Using these parameters, in a second step the local volatility part (Leverage function) of the SLV-model is directly approximated by an additional neural network.

Eric Brunner, eric.brunner@physik.uni-freiburg.de
