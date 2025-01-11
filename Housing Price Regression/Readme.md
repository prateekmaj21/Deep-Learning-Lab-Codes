# House Price Prediction Using Neural Networks

This project predicts house prices using a feedforward neural network built with PyTorch. It uses features like area, number of bedrooms, bathrooms, and binary categorical variables (e.g., air conditioning, furnishing status).

## Requirements

- numpy
- pandas
- torch
- sklearn
- matplotlib
- seaborn

## Dataset

The dataset includes the following columns:
- `price`, `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`, `furnishingstatus`

## Steps

1. **Import Libraries**
2. **Load Dataset**
3. **Preprocess Data**
   - Encode categorical variables
   - Split data into training and testing sets
   - Normalize features
4. **Build Neural Network Model**
5. **Train and Evaluate Model**

## License

This project is licensed under the MIT License.

