Anchorage House Price Predictor
This project is a simple web application that uses a machine learning model to predict house proces in Anchorage, Alaska. It is built with Python, using the Flask web framework and scikit-learn for the predictive model. 
The application provides an interactive form where users can input various features of a house to get an estimated price. 

Features: 
Interactive Web Interface: A user-friendly form makes it easy to input house details. 
Machine Learning Model: Uses a pre-trained scikit-learn model to make predictions. 
Flask Backend: The application's backend is powered by Flask, which hangles user requests and serves predictions. 
Local Deployment: Designed for easy setup and testing on a local machine. 

Getting Started: 
Follow these steps to get an application up and running on your local system. 
Prerequisites: 
You will need Python 3.6+ installed. You can install the necessary Python libraries using pip: 
BASH: pip install flask scikit-learn pandas pickle

Setup & Installation
1. Train and Save the Model:
First, a machine learning model needs to be trained on historical house data for Anchorage, AK, and saved as model.pkl. The provided code includes an example of how to create dummy `LinearRegression` model using sample data.
2. Create the Flask Application:
This is the core script that runs the web application. It handles loading the trained model, rendering the HTML template, and processing user input to generate a price prediction.
3. Create the HTML Template:
Create a folder named templates in the same directory as the Flask applicaiton file. Inside this folder, create a file named index.html. This file contains the HTML for the user interface, including the form for entering house features and displaying the predicted price.

Running the Applicaion: 
Once you have completed the setup, run the application from your terminal: 
python app.py

This command will start a local server. You can access the web application by opening your browswer and navigating to http://127.0.0.1:5000/. 
You should now see the "Anchorage House Price Prediction" form, where you can enter house features and get an estimated price. 
