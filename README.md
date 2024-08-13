# Credit Scoring Model and Data Processing Pipeline

This repository contains a comprehensive pipeline for credit scoring model development and deployment. It includes data preprocessing, feature scaling, model training, evaluation, and a Gradio-based web interface for real-time predictions.

## Features

- **Data Cleaning and Preparation**:
  - Functions to clean categorical and numerical data fields.
  - Handling of missing values and garbage data.
  - Data scaling using `StandardScaler`.

- **Model Training and Evaluation**:
  - Random Forest classifier for credit scoring.
  - Techniques for balancing datasets using SMOTE.
  - Evaluation metrics and model performance assessment.

- **Deployment**:
  - Saving and loading models and scalers using `joblib` and `pickle`.
  - Real-time prediction interface built with Gradio.

## File Structure
/credit-scoring-model
│
├── /data
│ ├── test.csv # Test dataset
│ ├── train.csv # Training dataset
│ └── ... # Additional datasets
│
├── /models
│ ├── scaler.pkl # Scaler for feature scaling
│ └── trained_model.pkl # Trained Random Forest model
│
├── /scripts
│ ├── data_processing.py # Functions for data cleaning and preprocessing
│ ├── model_training.py # Script for training the Random Forest model
│ ├── model_evaluation.py # Evaluation metrics and model assessment
│ ├── gradio_interface.py # Gradio interface for real-time predictions
│ └── utils.py # Utility functions used in the project
│
├── README.md # Project overview and setup instructions
├── requirements.txt # List of project dependencies
└── .gitignore # Specifies files and directories to be ignored by Git


## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/omarmokh122/CodeAlpha_Credit_Scoring_Mode.git

   cd CodeAlpha_Credit_Scoring_Mode

