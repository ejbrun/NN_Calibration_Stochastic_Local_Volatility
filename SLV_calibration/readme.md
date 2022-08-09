## Calibration of stochastic local volatility model via neural networks

### Dependencies:
- Tensorflow 1.15
- Keras 2.3.1

The notebook `SVL-calib-stochastic.ipynb` contains the calibration of the stochastic part (Heston model) of the SLV model. The calibrated Heston-parameters are imported to `SLV-calib-local.ipynb`, in which the local volatility is calibrated by means of a deep neural network learning the Leverage function. A detailed project description and the discussion of the calibration results are given in `deep_calibration_SLV_model.pdf`.

Eric Brunner, eric.brunner@physik.uni-freiburg.de
