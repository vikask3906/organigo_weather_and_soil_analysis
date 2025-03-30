# Smart Crop Suitability and Weather Forecasting with LSTM

## Overview
This project helps farmers and agricultural enthusiasts make informed decisions using real-time weather forecasts and AI-powered temperature predictions. By combining weather data with crop suitability analysis, it determines the best times for sowing and harvesting different crops.

## What This Project Does
- Fetches real-time weather data using the Agro Monitoring API
- Uses an LSTM model to predict future temperature trends
- Analyzes crop suitability based on upcoming weather conditions
- Visualizes predictions with easy-to-understand graphs and tables

## How It Works
![Workflow Diagram](https://upload.wikimedia.org/wikipedia/commons/5/54/Weather_forecasting_process.png)
A simple illustration of how weather forecasting and AI predictions work together.

## Dependencies
Before getting started, ensure you have the following installed:
```bash
pip install keras requests numpy pandas matplotlib scikit-learn
```

## Steps to Get Started
### Fetch Weather Data
The script retrieves temperature, humidity, and rainfall data from the Agro Monitoring API for a specific location.

### Train an LSTM Model
The model learns from historical weather data to predict future temperature trends.

### Check Crop Suitability
The program compares forecasted weather with optimal crop conditions to determine which crops can be sown or harvested in the coming days.

## What You Will See
This project generates:
- Time-series plots showing actual versus predicted temperatures
- Crop suitability tables based on upcoming weather conditions

## How to Use It
1. Clone this repository:
```bash
git clone https://github.com/yourusername/weather-crop-lstm.git
cd weather-crop-lstm
```
2. Run the Jupyter Notebook or open it in Google Colab.
3. Set your latitude and longitude to match your location.
4. Train the model and observe the predictions.

## Sample Output
### Temperature Prediction Plot
![Temperature Forecast](https://upload.wikimedia.org/wikipedia/commons/8/89/Time_series_temperature_prediction_example.png)

### Crop Suitability Table
| Crop   | Suitable to Sow | Suitable to Harvest |
|--------|---------------|------------------|
| Rice   | Yes        | No            |
| Wheat  | No         | Yes           |

## License
This project is open-source and available under the MIT License. Feel free to modify and improve it.

## Want to Contribute?
Contributions are welcome. Fork the repository, open an issue, or submit a pull request to enhance this project further. Happy coding!



