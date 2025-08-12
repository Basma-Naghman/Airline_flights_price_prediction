Airline Flight Price Prediction
📌 Overview
This project predicts airline flight prices based on various factors such as airline, source, destination, travel dates, and times. The goal is to build a machine learning model that can accurately estimate ticket prices, helping customers and businesses make better travel decisions.

📂 Dataset
The dataset contains flight details with the following features:

Airline — Name of the airline.

Date of Journey — Date when the flight is scheduled.

Source — Starting city.

Destination — Arrival city.

Dep Time — Departure time.

Arrival Time — Arrival time.

Duration — Total travel time.

Total Stops — Number of stops.

Additional Info — Miscellaneous details.

Price (Target) — Ticket price in INR.

⚙️ Approach
Data Preprocessing

Handle missing values.

Convert categorical variables using One-Hot Encoding.

Extract time-based features from date/time columns.

Normalize numerical features.

Model

A Deep Neural Network (DNN) built using TensorFlow/Keras.

Loss: MSE (Mean Squared Error)

Metrics: MAE, MSE, R² Score

Training

50 epochs, batch size determined experimentally.

Early stopping/checkpointing possible for optimization.

Evaluation

Train R² ≈ 0.9719

Validation R² ≈ 0.9694

Average MAE ≈ 2,100 INR

📊 Results
The model achieved strong performance:

High R² (~0.97) indicates excellent predictive power.

Low MAE (~₹2K) shows predictions are close to actual ticket prices.
