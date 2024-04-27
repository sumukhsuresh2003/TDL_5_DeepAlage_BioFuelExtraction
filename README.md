# TDL_5_DeepAlage_BioFuelExtraction
# Biofuel Production Forecasting with LSTM

This Jupyter Notebook contains a Python script for forecasting the optimal timeframe for the production of biofuel from algae using Long Short-Term Memory (LSTM) neural networks.

## Dataset

The dataset used for training the LSTM model is stored in a CSV file named `merged_algae_dataset.csv`. This dataset contains various features related to algae cultivation, including **lipid content**, **protein content**, **carbohydrate content**, **algal culture temperature**, **algal culture pH**, **algal culture depth**, and **duration**.

## Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib

## Usage

1. **Load Dataset**: Load the CSV dataset containing the algae cultivation data.

2. **Prepare Data**: Format the dataset for input to the LSTM model.

3. **Define Model**: Specify the architecture of the LSTM model using Keras.

4. **Compile Model**: Compile the model with the chosen optimizer and loss function.

5. **Train Model**: Train the model with the prepared data.

6. **Plot Predictions**: Visualize the actual vs. predicted values for assessment.

7. **Forecast Optimal Timeframe**: Determine the optimal timeframe for biofuel extraction based on specified criteria.

Adjust parameters and paths as needed to suit your dataset and requirements.
