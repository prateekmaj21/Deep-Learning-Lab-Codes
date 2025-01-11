# California Housing Price Prediction

This project uses a neural network model to predict the median house value in California districts based on various features such as median income, house age, number of rooms, and more. The dataset used is the **California Housing dataset**, which includes information on housing prices and related features for different block groups in California.

## Project Overview

The goal of this project is to build a model that can predict the median house value (in USD 100,000) for a given district based on 8 input features:

- **MedInc**: Median income in the block group
- **HouseAge**: Median house age in the block group
- **AveRooms**: Average number of rooms per household
- **AveBedrms**: Average number of bedrooms per household
- **Population**: Population of the block group
- **AveOccup**: Average number of household members
- **Latitude**: Latitude of the block group centroid
- **Longitude**: Longitude of the block group centroid

## Installation

To run this project, you need to install the following dependencies:

```bash
pip install torch numpy scikit-learn matplotlib
