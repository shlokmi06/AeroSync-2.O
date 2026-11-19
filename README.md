# ✈️ AeroSync

AeroSync analyzes U.S. flight delays using flight, airline, airport, and weather data. It includes an end-to-end data workflow, interactive visualizations, a baseline machine-learning pipeline, and a Streamlit dashboard.

## Features

- Load flight data from Kaggle, uploaded files, or a synthetic fallback
- Clean data and engineer time, route, congestion, and weather features
- Explore delay patterns with interactive Plotly charts
- Prepare features for a time-based machine-learning workflow
- Filter and explore results in a Streamlit dashboard

## Tech stack

Python · pandas · NumPy · scikit-learn · Plotly · Streamlit

## Run in Google Colab

1. Open `AeroSync_(1).ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Add `NGROK_AUTHTOKEN` to Colab Secrets to launch the public dashboard.
4. Optionally add Kaggle credentials to use the real flight dataset. Without them, the notebook can generate synthetic data.

The dashboard stays available while the notebook runtime is running.

## Data note

The notebook’s saved run used synthetic data. Treat its displayed results as a demonstration, not as findings about actual flight operations.

## License

See [LICENSE](LICENSE).
