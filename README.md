# Iris Flower Classification Web App

A Flask web application for classifying iris flowers based on their sepal and petal measurements.

## Features
- Predicts iris species (setosa, versicolor, virginica) from input measurements
- Simple web interface for easy interaction
- Pre-trained machine learning model included

## Installation

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download the model and scaler files (if not included in repository)

## Usage

Run the application:
```bash
python app.py
```

The web interface will be available at:
```
http://localhost:10000
```

## API Endpoint

- **URL**: `/`
- **Method**: `POST`
- **Parameters** (form-data):
  - sepal_length (float)
  - sepal_width (float)
  - petal_length (float)
  - petal_width (float)

## Example Input
```
sepal_length: 5.1
sepal_width: 3.5
petal_length: 1.4
petal_width: 0.2
```

## Requirements
- Python 3.x
- Flask
- scikit-learn
- joblib
- numpy

## License
[MIT](https://choosealicense.com/licenses/mit/)
#
