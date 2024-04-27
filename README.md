# Biofuel Production Forecasting with LSTM

This repository contains a Python script for forecasting the optimal timeframe for the production of biofuel from algae using Long Short-Term Memory (LSTM) neural networks.

## Dataset

The dataset used for training the LSTM model is stored in a CSV file named `merged_algae_dataset.csv`. This dataset contains various features related to algae cultivation, including lipid content, protein content, carbohydrate content, algal culture temperature, algal culture pH, algal culture depth, and duration.

## Requirements

- Python 3.x
- Tensorflow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib

## Usage

1. **Load Dataset**: Load the CSV dataset containing the algae cultivation data.

2. **Prepare Data**: Prepare the data for input to the LSTM model by specifying the number of input and output time steps (`n_steps_in` and `n_steps_out`, respectively). This involves formatting the dataset appropriately for LSTM input.

3. **Define Model**: Define the architecture of the LSTM model using Keras. The model consists of an encoder-decoder structure with multiple LSTM layers and dropout regularization.

4. **Compile Model**: Compile the defined model using an appropriate optimizer and loss function. In this example, Mean Absolute Error (MAE) loss and the Adam optimizer are used.

5. **Train Model**: Train the compiled model using the prepared data. You can specify the number of epochs, batch size, and early stopping criteria during training.

6. **Evaluate Model**: After training, the model can be evaluated using various metrics or used for making predictions.

7. **Plot Predictions**: Visualize the actual vs. predicted values for a specific feature to assess the model's performance.

8. **Forecast Optimal Timeframe**: Finally, the script identifies the optimal timeframe for biofuel extraction based on specified criteria such as lipid content, protein content, carbohydrate content, algal culture temperature, algal culture pH, and algal culture depth.

## Criteria for Optimal Timeframe

The optimal timeframe for biofuel extraction is determined based on the following criteria:

- Lipid content above 20%
- Protein content between 10% and 30%
- Carbohydrate content between 10% and 30%
- Algal culture temperature between 20°C and 25°C
- Algal culture pH between 7 and 9
- Algal culture depth less than 30 cm

## Example Usage

You can open and run this Jupyter Notebook in your local environment or any compatible platform.
