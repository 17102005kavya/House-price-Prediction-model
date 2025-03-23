# House Price Prediction Model

## Overview
This project implements a house price prediction model using Decision Trees and a custom Random Forest algorithm. The model is trained to predict house prices based on various input features.

## Dataset
The dataset used contains various attributes of houses, such as:
- Area
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Parking availability
- Furnishing status, etc.

## Model Details
- **Decision Trees**: A single tree-based model that learns from training data by recursively splitting features.
- **Custom Random Forest**: An ensemble of multiple decision trees trained on bootstrapped samples to improve accuracy and generalization.

## Training Details
- The model is trained using Mean Squared Error (MSE) as the loss function.
- Training is conducted over multiple iterations to minimize loss.

## Training Performance
```
Iteration 0, Loss: 3.544485569000244
Iteration 1000, Loss: 0.007393213454633951
Iteration 2000, Loss: 0.0073700412176549435
Iteration 3000, Loss: 0.007369940634816885
Train MSE: 0.007369939237833023
Test MSE: 0.012988480739295483
```

## Dependencies
To run the model, install the required dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
1. Load the dataset.
2. Preprocess the data (handle missing values, encode categorical variables, normalize numerical features).
3. Train the model using Decision Trees or Custom Random Forest.
4. Evaluate the model performance using MSE.
5. Predict house prices for new data points.

## Future Improvements
- Optimize hyperparameters for better accuracy.
- Experiment with additional ensemble techniques (e.g., Gradient Boosting, XGBoost).
- Deploy as a web application for user interaction.

## Author
Kavya Nair

