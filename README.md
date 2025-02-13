# Solar Power Prediction

## Project Overview

This project focuses on predicting solar power generation using various meteorological parameters. By leveraging machine learning techniques, the model aims to estimate the generated power (in kW) based on environmental and atmospheric conditions.

## Dataset

The dataset includes key features that influence solar power generation:

- **temperature\_2\_m\_above\_gnd**: Temperature at 2 meters above the ground.
- **relative\_humidity\_2\_m\_above\_gnd**: Humidity level at 2 meters above the ground.
- **total\_cloud\_cover\_sfc**: Total cloud cover at the surface.
- **shortwave\_radiation\_backwards\_sfc**: Backward shortwave radiation at the surface.
- **wind\_speed\_10\_m\_above\_gnd**: Wind speed at 10 meters above the ground.
- **angle\_of\_incidence**: Angle of solar incidence.
- **zenith**: Solar zenith angle.
- **azimuth**: Solar azimuth angle.
- **generated\_power\_kw**: Target variable representing the generated power in kilowatts.

## Project Structure

- [`Dataset_analysis.ipynb`](https://github.com/Jay0073/Solar-Power-Prediction/blob/main/Dataset_analysis.ipynb): Exploratory Data Analysis (EDA) and feature engineering.
- [`Model_building.ipynb`](https://github.com/Jay0073/Solar-Power-Prediction/blob/main/Model_building.ipynb): Machine learning model development and evaluation.

## Installation

To run this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Jay0073/Solar-Power-Prediction.git
```
```bash
cd Solar-Power-Prediction
```
```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebooks to analyze the dataset and train the model:

```bash
jupyter notebook Dataset_analysis.ipynb
```
```bash
jupyter notebook Model_building.ipynb
```

## Model Performance

The model is evaluated based on metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score to assess prediction accuracy.

## Future Work

- Improving model accuracy with feature selection and hyperparameter tuning.
- Deploying the model using Flask, FastAPI, or Streamlit.
- Integrating real-time weather data for dynamic predictions.

## Contributions

Contributions are welcomed! Feel free to submit issues, fork the repository, and create pull requests.

