# HVAC Optimization in Labs

This project focuses on optimizing cooling needs in laboratory environments using machine learning. It features a Decision Tree model to forecast cooling requirements based on occupancy and temperature data, visualized through a Streamlit dashboard with zone-wise heatmaps.

## Features
- **Predictive Modeling**: Decision Tree Regressor for cooling load forecasting.
- **Interactive Dashboard**: Real-time zone forecasts and heatmaps.
- **Synthetic Data Generation**: Customizable lab environment simulator.

## How it Works
1. **Data Collection**: The system uses synthetic sensors for occupancy, ambient temperature, and equipment power usage across multiple zones (Lab A, Lab B, Clean Room, Office 1).
2. **AI Modeling**: A Decision Tree Regressor is trained on historical data to map these inputs to the required cooling load (kW).
3. **Forecasting**: The dashboard allows users to simulate "what-if" scenarios by adjusting occupancy and temperature, visualizing the impact on cooling needs instantly.

## Dashboard Preview
- **Zone Metrics**: Real-time cooling demand per zone.
- **Heatmaps**: Visual representation of heat distribution over the lab floor.
- **Trend Charts**: Historical analysis of cooling requirements over the past 24 hours.

## Technical Details
- **Model**: Scikit-Learn DecisionTreeRegressor (Depth=5)
- **Visualization**: Plotly Express for heatmaps and time-series plots.
- **Backend**: Streamlit for the interactive UI.
