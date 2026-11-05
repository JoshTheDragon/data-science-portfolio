# Fraud Detection System

A machine learning pipeline designed to detect fraudulent transactions using advanced classification algorithms and feature engineering techniques.

## Overview

This project implements a complete fraud detection system with data preprocessing, model training, and evaluation capabilities. The system uses machine learning to identify patterns in transaction data that may indicate fraudulent activity.

## Features

- **Data Preprocessing:** Cleaning and transforming raw transaction data
- **Feature Engineering:** Creating meaningful features from transaction attributes
- **ML Pipeline:** Automated model training and evaluation pipeline
- **Model Persistence:** Saved model for production use
- **Analysis Notebook:** Exploratory data analysis with visualizations

## Tech Stack

- **Python:** Primary programming language
- **scikit-learn:** Machine learning algorithms
- **pandas:** Data manipulation and analysis
- **numpy:** Numerical computing
- **Jupyter Notebook:** Interactive analysis

## Project Structure

```
Fraud Detention copy/
├── AIML Dataset.csv          # Training dataset (not included in repo)
├── Analysis_Model.ipynb      # Exploratory analysis notebook
├── fraud_detention.py        # Main ML pipeline script
├── Fraud_detention_pipeline.pkl  # Trained model (saved)
├── pyproject.toml            # Project dependencies
└── README.md                  # This file
```

## Installation

1. Navigate to the project directory:
```bash
cd "resume portfolo projects/Fraud Detention copy"
```

2. Install dependencies:
```bash
pip install -r pyproject.toml
# or using uv
uv pip install -r pyproject.toml
```

## Usage

### Running the ML Pipeline

```bash
python fraud_detention.py
```

### Exploratory Analysis

Open the Jupyter notebook:
```bash
jupyter notebook Analysis_Model.ipynb
```

## Dataset

The project uses the AIML Dataset for training the fraud detection model. Due to its size (471 MB), the dataset is not included in this repository.

**Note:** Place `AIML Dataset.csv` in the project directory to run the analysis.

## Model Performance

The trained model is saved as `Fraud_detention_pipeline.pkl` and can be loaded for inference:

```python
import pickle

with open('Fraud_detention_pipeline.pkl', 'rb') as f:
    model = pickle.load(f)

# Use model for predictions
predictions = model.predict(new_data)
```

## Key Insights

The analysis notebook includes:
- Data distribution analysis
- Feature importance visualization
- Model performance metrics
- Confusion matrix and classification report

## Future Improvements

- [ ] Add real-time prediction API
- [ ] Implement ensemble methods
- [ ] Add explainability (SHAP values)
- [ ] Deploy as a web service

## License

This project is for educational and portfolio purposes.
