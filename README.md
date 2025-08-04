# car-price-prediction
A simple and user-friendly web app built with Flask and Machine Learning to estimate the resale value of a car based on user input.
<img width="1919" height="869" alt="Screenshot 2025-08-03 161950" src="https://github.com/user-attachments/assets/941fbcff-361f-41d7-824b-1a4f160f210a" />

## Features
⦁	Interactive UI using HTML/CSS
⦁	Uses a trained Random Forest Regression model
⦁	Predicts resale value based on:
⦁	Year of manufacture
⦁	Present price
⦁	Kilometers driven
⦁	Fuel type
⦁	Number of owners
⦁	Transmission type
⦁	Seller type
## How It Works
⦁	The app uses a Random Forest Regression model trained on a dataset of car sales.

⦁	The model is saved using pickle and loaded in the Flask backend.

⦁	A form collects the car's details from the user.

⦁	The model predicts the resale price and displays it on the same page.
