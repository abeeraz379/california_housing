# 📊 Project Summary: California Housing Price Prediction
- By : ABeer AL-Zebda | Ml Engineer
## 🎯 Objective

The goal of this project is to build a machine learning model using a Neural Network to predict housing prices in California based on several input features such as location, income, and housing characteristics.

***

## 📂 Dataset

The project uses the **California Housing dataset** from the `scikit-learn` library, which includes:

*   ✅ 8 input features (e.g., median income, number of rooms, location)
*   ✅ 1 target variable: **MedHouseVal** (median house value)

***

## ⚙️ Methodology

### 1. Data Loading

### 2. Data Preparation

*   The dataset was split into:
    *   **X** → input features
    *   **y** → target variable
*   Feature scaling was applied to improve model performance.

***

### 3. Model Building

A Neural Network model was built using Keras with:

*   Input layer: 8 features
*   Hidden layers: Dense layers with ReLU activation
*   Output layer: Single neuron for regression


***

### 4. Model Compilation

The model was compiled using:

*   ✅ Loss Function: Mean Squared Error (MSE)
*   ✅ Optimizer: Adam
*   ✅ Evaluation Metric: R² Score

***

### 5. Training

The model was trained over several epochs to learn the relationship between features and house prices.

***

## 📈 Model Evaluation
The model performance was evaluated using **R² (R-squared)**:
*  **R²=  0.8198** for training data
*  **R²=  0.7901** for cross validation data
*  The model achieved a reasonable R² score, indicating a good ability to explain the variability in housing prices.

***

## ✅ Results

*   The model successfully predicted house prices close to actual values
*   Performance improved with:
    *   Data scaling
    *   Increasing network complexity

***

## 📌 Conclusion

This project demonstrates how Neural Networks can be used for **regression tasks**.  
Using tools like **scikit-learn** and **TensorFlow/Keras**, the model learns patterns in the data and predicts continuous values effectively.

***

