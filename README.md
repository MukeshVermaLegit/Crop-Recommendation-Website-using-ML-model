# Crop Recommendation System

This project is a Crop Recommendation System that predicts the best crop to cultivate based on soil and environmental conditions. The application is built using Flask and employs a machine learning model to make predictions.

## Project Structure

- `app.py`: The main Flask application that handles routes and logic for predictions.
- `model.pkl`: The pre-trained machine learning model used for predictions.
- `standscaler.pkl`: The pre-fitted StandardScaler object used to scale the input features.
- `minmaxscaler.pkl`: The pre-fitted MinMaxScaler object used to normalize the input features.
- `templates/`:
  - `index.html`: The HTML template for the input form and displaying the prediction result.
- `static/`: Directory for static files like CSS and images (optional).

## Prerequisites

To run this project, you'll need the following installed:

- Python 3.x
- Flask
- Scikit-learn
- Pandas
- Numpy
- Pickle

You can install the required Python packages using the following command:

```bash
pip install flask scikit-learn pandas numpy
