# Demand Forecasting ML Project

A comprehensive machine learning project for demand forecasting using multiple models (ARIMAX, ML models, LSTM, TFT) with expanding window validation.

## Features

- **Multiple Models**: ARIMAX, Random Forest, XGBoost, LightGBM, LSTM, Temporal Fusion Transformer
- **Hybrid Model**: Combines predictions from multiple models
- **Advanced Feature Engineering**: Temporal, lag, rolling, and external features
- **Expanding Window Validation**: Robust time series cross-validation
- **Clean Architecture**: Modular, maintainable, and extensible code

## Project Structure

```
demand_forecasting/
│
├── README.md
├── requirements.txt
├── config/
│   └── config.yaml
├── data/
│   └── raw/
│       └── sales_data.csv
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   ├── validation/
│   ├── evaluation/
│   └── utils/
├── notebooks/
└── main.py
```

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

## Configuration

Edit `config/config.yaml` to customize:
- Feature engineering parameters
- Model hyperparameters
- Validation settings
- Data paths

## Models

- **ARIMAX**: Statistical time series model with exogenous variables
- **ML Models**: Random Forest, XGBoost, LightGBM
- **LSTM**: Deep learning recurrent neural network
- **TFT**: Temporal Fusion Transformer with attention mechanism
- **Hybrid**: Weighted ensemble of all models

## License

Private Project
