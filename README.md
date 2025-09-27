# Housing Price Prediction

This project aims to predict housing prices based on various features of houses. It explores different regression models to find the best performing one for this dataset.

## Dataset

The project uses the `Housing.csv` dataset, which contains information about houses, including their price, area, number of bedrooms, bathrooms, and other amenities.

## Methodology

The project follows these steps:

1.  **Data Loading and Preprocessing:** The `Housing.csv` dataset is loaded and preprocessed. This includes one-hot encoding of categorical features to prepare the data for machine learning models.
2.  **Model Training and Evaluation:** Several regression models are trained on the preprocessed data. The performance of each model is evaluated to determine the best model for predicting housing prices.

## Models

The following regression models are implemented and compared in this project:

*   Linear Regression
*   Multiple Linear Regression
*   K-Nearest Neighbors (KNN)
*   Random Forest
*   Gradient Boosting

## Getting Started

### Prerequisites

*   Python 3
*   Jupyter Notebook or JupyterLab

### Installation

1.  Clone this repository:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd Housing_Prediction
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  Open the Jupyter notebook:
    ```bash
    jupyter notebook Housing_Prediction.ipynb
    ```
2.  Run the cells in the notebook to see the analysis and the results.