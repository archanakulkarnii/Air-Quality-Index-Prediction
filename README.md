Air Quality Index (AQI) Prediction

This project predicts the Air Quality Index (AQI) based on key air pollutant concentrations using a Linear Regression model.
It features a Tkinter-based user interface where users can input pollutant values, predict AQI, and visualize actual vs predicted results.

🚀 Features

Predicts AQI from PM2.5, PM10, NO2, SO2, CO, and O3 values.

Categorizes AQI into Good, Moderate, Unhealthy, Very Unhealthy, and Hazardous.

Input validation – prevents entering invalid values.

Graph visualization – plot actual vs predicted AQI.

🛠️ Tech Stack

Python 3.x

Tkinter – for the graphical user interface

Pandas & NumPy – for data handling

Scikit-learn – for Linear Regression model

Matplotlib – for visualization

📂 Project Structure
.
├── datasetaqi.csv       # Dataset file (replace with your AQI dataset)
├── aqi_prediction.py    # Main application code
└── README.md            # Project documentation

⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/aqi-prediction.git
cd aqi-prediction


Install dependencies:

pip install -r requirements.txt


Run the application:

python aqi_prediction.py

📊 How It Works

The model is trained on the AQI dataset (datasetaqi.csv).

Users enter pollutant concentrations in the Tkinter interface.

The app predicts AQI and displays the AQI value and category.

Clicking "Plot Results" shows a comparison graph of actual vs predicted AQI.

📌 Example

Input:

PM2.5 = 70
PM10  = 120
NO2   = 40
SO2   = 10
CO    = 0.8
O3    = 25


Output:

Predicted AQI: 135.42
Category: Unhealthy for Sensitive Groups
