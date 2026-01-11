# prophet-lstm-energy-forecasting

This repository implements a hybrid time-series forecasting framework using Prophet and LSTM to predict hourly electricity consumption across multiple regions.
The project combines trend and seasonality modeling from Prophet with nonlinear temporal learning from LSTM to improve forecasting accuracy and stability.
It includes five hybrid architectures: residual, feature-augmented, weighted ensemble, stacking, and error-correction models.
The system uses symbolic, statistical, and FFT-based features along with Prophet components and LSTM embeddings to build a rich hybrid dataset.
Models are evaluated using R², RMSE, PRR, CPI, and residual entropy to ensure accuracy, generalization, and reliable uncertainty estimation.
