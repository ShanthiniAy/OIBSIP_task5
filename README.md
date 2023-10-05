# OIBSIP_task5

# Sales Prediction Model Deployment

This repository contains code and instructions for deploying a machine learning model for sales prediction using Flask.

## Project Overview

In this project, we have developed a machine learning model to predict future sales based on historical data. The model is trained using scikit-learn and deployed as a web service using Flask. This README provides step-by-step instructions on how to deploy the model and make predictions for new data points.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- scikit-learn
- pandas
- requests

You can install the required Python packages using `pip`. For example:

```bash
pip install flask scikit-learn pandas requests
```

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/sales-prediction-deployment.git
cd sales-prediction-deployment
```

2. Download the trained machine learning model (e.g., `model.pkl`) and place it in the root directory of the project.

## Usage

### Deployment

1. Run the Flask application to deploy the model:

```bash
python app.py
```

By default, the Flask app will run on `http://localhost:5000`. You can change the host and port in the `app.py` file.

### Making Predictions

To make predictions for new data points, you can use the provided Python script `predict.py`. Edit the `new_data_point` dictionary in `predict.py` with your own data and run the script:

```bash
python predict.py
```

The script will send a POST request to the Flask API and display the predictions.

## Customization

- You can customize the model training code in `train_model.py` to use your own data and features.
- Modify the Flask API code in `app.py` if you need to change the input data format or response format.
- Customize the error handling and input validation as needed.


