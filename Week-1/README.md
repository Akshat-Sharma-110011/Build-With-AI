# Air Quality Index (AQI) Predictor

## Overview
The **Air Quality Index (AQI) Predictor** is a machine learning project designed to analyze environmental factors and predict air pollution levels. This project processes data from various meteorological sources and predicts AQI values using statistical and machine learning models.

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Machine learning model for AQI prediction
- Visualization of AQI trends
- Model evaluation and performance metrics

## Dataset
The dataset contains meteorological features such as:
- **T**: Temperature (°C)
- **TM**: Maximum Temperature (°C)
- **Tm**: Minimum Temperature (°C)
- **SLP**: Sea Level Pressure (hPa)
- **H**: Humidity (%)
- **VV**: Visibility (km)
- **V**: Wind Speed (km/h)
- **VM**: Maximum Wind Speed (km/h)
- **PM 2.5**: Particulate Matter concentration (µg/m³) - Target variable

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AQI-Predictor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AQI-Predictor
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter Notebook to execute the AQI prediction workflow:
```bash
jupyter notebook Air-Quality-Index-Predictor-Updated.ipynb
```

## Results
The model predicts AQI values based on meteorological inputs and provides visualizations for insights into pollution trends.

## Contributing
Feel free to fork the repository, submit issues, or contribute enhancements via pull requests.

## License
This project is licensed under the MIT License.
