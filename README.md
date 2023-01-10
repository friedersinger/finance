# README

This is a Python web application built with the Flask framework. The application simulates a stock trading platform where users can buy and sell stocks and view their transaction history.

## Required Libraries

- cs50
- flask
- flask_session

### These libraries can be installed by running the following command in the terminal:

pip install cs50 flask flask_session

## Copy code

pip install cs50 flask flask_session

## Usage

Run the application using the command flask run
Open the application in your web browser by navigating to http://localhost:5000
Register for an account or login with an existing account
Once logged in, you will be able to buy and sell stocks, view your transaction history, and check your current portfolio.

## Key Features

Registration and Login System: The application includes a registration and login system that securely stores user's information in a SQLite database.
Stock Transactions: Users can buy and sell stocks using real-time stock information obtained via an external API.
Transaction History: Users can view a history of their previous stock transactions.
Portfolio View: Users can see the stocks they own and the total value of their portfolio.

## File Structure

`helpers.py` contains helper functions used throughout the application.
`application.py` contains the main logic of the application, including routes and the Flask application instance.
`templates/` directory contains HTML templates used to render the application's views.
`static/` directory contains CSS and JavaScript files used to style and add interactivity to the application's views.

## Note

Make sure to set up an API_KEY from an external source for the Stock Lookup functionality as the original API_KEY is not provided in the code.
