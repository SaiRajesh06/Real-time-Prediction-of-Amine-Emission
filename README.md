# Real-time-Prediction-of-Amine-Emission

## Problem Statement
Predicting amine emissions in carbon capture systems is a complex task due to numerous factors such as design and operating conditions. To improve prediction accuracy, we employed advanced machine learning techniques.

## Approach
We utilized a deep learning approach using an LSTM autoencoder model, which is well-suited for analyzing time-series data. The autoencoder consists of the following components:

- Encoder: Generates compact data representations
- Decoder: Reconstructs the original data
- Dense layers: Predict amine emissions outputs

## Data Preprocessing
We performed correlation-based feature selection, normalization, and other preprocessing steps on data collected with measurements taken every 10 minutes over a period of 2 weeks.

## Results
Our preliminary results are quite promising, with a mean absolute percentage error below 10%. The low percentage errors highlight the potential of this LSTM autoencoder approach to provide more precise amine emission forecasting compared to traditional modeling techniques. However, the majority of points still track reasonably close.

## Future Work
In the future, we plan to explore other deep learning architectures, such as CNN-LSTM hybrids and attentional mechanisms, to further improve the prediction accuracy.

## Summary
This research showcases how advanced machine learning, particularly deep learning, can provide a powerful solution for the complex task of predicting amine and degradation product emissions in carbon capture systems.
