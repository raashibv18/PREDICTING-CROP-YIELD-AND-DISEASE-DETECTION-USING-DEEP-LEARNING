# Predicting Crop Yield and Disease Detection Using Deep Learning

## Overview
This project leverages deep learning techniques to enhance agricultural practices by accurately predicting crop yields and detecting plant diseases. The implementation includes two key models:
- **LSTM-based Crop Yield Prediction**: Forecasts crop yield based on historical weather, soil, and yield data.
- **CNN-based Disease Detection**: Identifies plant diseases from leaf images with high classification accuracy.

By integrating AI-driven solutions, this project empowers farmers with real-time insights to optimize resources, minimize losses, and promote sustainable farming.

## Features
- **Long Short-Term Memory (LSTM) Model** for analyzing time-series agricultural data.
- **Convolutional Neural Network (CNN) Model** for real-time disease detection.
- **Automated Data Processing** for enhanced accuracy.
- **User-friendly Interface** for farmers and agricultural planners.
- **Scalable & Adaptable** to various crop types and environmental conditions.

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn

## Dataset
- **Crop Yield Prediction**: Historical data on climate, soil properties, and past yield records.
- **Disease Detection**: Image dataset of plant leaves affected by different diseases.
- Datasets sourced from **Kaggle and agricultural databases**.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crop-yield-disease-detection.git
   cd crop-yield-disease-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download or prepare the datasets and place them in the `data/` directory.

## Usage
### 1. Crop Yield Prediction
- Run the LSTM model:
   ```bash
   python crop_yield_prediction.py
   ```
- Provide input parameters (weather conditions, soil properties, etc.).
- View yield forecast results.

### 2. Disease Detection
- Run the CNN model:
   ```bash
   python disease_detection.py
   ```
- Upload a leaf image.
- View disease classification results.

## Results
- **LSTM Model** achieves high accuracy in yield prediction, helping farmers make informed decisions.
- **CNN Model** classifies plant diseases with over 90% accuracy, enabling early detection and intervention.

## Applications
- **Precision Agriculture**: Optimizes farming decisions with AI insights.
- **Smart Farming Systems**: Integrates with IoT devices for real-time monitoring.
- **Crop Health Monitoring**: Detects diseases early to prevent losses.
- **Sustainability Initiatives**: Reduces resource waste and enhances food security.

## Future Enhancements
- Integration with **IoT sensors** for real-time environmental monitoring.
- Mobile application for farmers to access predictions instantly.
- Expansion to support **multi-crop analysis** and diverse farming regions.



