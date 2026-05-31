# Mobile Price Prediction MLOps Project

## Project Overview

This project predicts mobile price range using machine learning.

## Features

- Data Analysis (EDA)
- Model Training
- FastAPI API
- Prediction Endpoint

## Project Structure

mobile-price-mlops/

├── data/

├── models/

├── notebooks/

├── src/

├── requirements.txt

└── README.md


## Run Project

Create virtual environment:

python -m venv venv

Activate:

venv\Scripts\activate

Install packages:

pip install -r requirements.txt

Run API:

uvicorn src.app:app --reload

Open:

http://127.0.0.1:8000

Prediction endpoint:

http://127.0.0.1:8000/predict