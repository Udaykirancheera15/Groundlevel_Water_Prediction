
# Groundlevel Water Prediction

This repository contains a machine learning project aimed at predicting groundwater levels using various models, including linear regression, random forest, support vector regression (SVR), and XGBoost. The project also includes a web application for demonstrating the predictions.

## Project Structure

- **DATASCIENCE.ppt** - A presentation covering the data science process, insights, and findings related to the groundwater prediction project.
- **District_Statewise_Well.csv** - Dataset used for training and testing the machine learning models. This file includes data on groundwater levels from different districts and states.
- **Linear regression.ipynb** - Jupyter Notebook implementing a linear regression model for predicting groundwater levels.
- **Random forest.ipynb** - Jupyter Notebook implementing a random forest model to improve the accuracy of predictions.
- **SVR.ipynb** - Jupyter Notebook implementing a support vector regression model, particularly useful for handling non-linear data.
- **xg boost.ipynb** - Jupyter Notebook implementing an XGBoost model, a robust and efficient model for regression tasks.
- **app.py** - Python script for the web application. This app uses a trained model to predict groundwater levels based on user inputs.
- **groundwater_model.pkl** - Serialized machine learning model (pickle file) used by the web application for predictions.
- **templates/** - Directory containing HTML templates for the web application.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages (see [requirements.txt](#creating-requirements.txt))
- Jupyter Notebook (for exploring `.ipynb` files)

### Installation

1. Clone this repository:
   ```bash
   git clone git@github.com:Udaykirancheera15/Groundlevel_Water_Prediction.git
   cd Groundlevel_Water_Prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the web application:
   ```bash
   python app.py
   ```

### Creating `requirements.txt`

To generate `requirements.txt`, you can use:
   ```bash
   pip freeze > requirements.txt
   ```

## Usage

1. Explore the Jupyter Notebooks to understand how each model works:
   - `Linear regression.ipynb`
   - `Random forest.ipynb`
   - `SVR.ipynb`
   - `xg boost.ipynb`

2. Run `app.py` to launch the web application. This application takes user input and predicts groundwater levels using the pre-trained model (`groundwater_model.pkl`).

3. Refer to `DATASCIENCE.ppt` for insights and a summary of the project.

## Project Files

| File                          | Description                                               |
|-------------------------------|-----------------------------------------------------------|
| **DATASCIENCE.ppt**           | Presentation for the data science process and findings    |
| **District_Statewise_Well.csv** | Dataset with groundwater level information               |
| **Linear regression.ipynb**   | Linear Regression model implementation                    |
| **Random forest.ipynb**       | Random Forest model implementation                        |
| **SVR.ipynb**                 | Support Vector Regression (SVR) model implementation      |
| **xg boost.ipynb**            | XGBoost model implementation                              |
| **app.py**                    | Web application for predicting groundwater levels         |
| **groundwater_model.pkl**     | Serialized model for use in `app.py`                      |
| **templates/**                | HTML templates for the web application                    |

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

