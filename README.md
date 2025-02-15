# Customer-Churn-Prediction

## Overview
This project predicts customer churn using a Decision Tree model and visualizes the results using Plotly.

## Features
- Preprocesses the customer churn dataset (handles missing values, balances data, standardizes features).
- Trains a Decision Tree Classifier to predict customer churn.
- Evaluates model performance using accuracy metrics.
- Visualizes churn prediction results using Plotly scatter plots.
- **Dataset**: The dataset is sourced from Telecom Customer Churn Data.

## Visualization
Plotly is used to create an interactive scatter plot showing predicted churn based on tenure and total charges.

## Installation & Usage

1. **Install Dependencies**
   ```bash
   pip install pandas numpy plotly scikit-learn matplotlib
   ```

2. **Run the Script**
   ```bash
   python customer_churn.py
   ```

3. **Output**
     Decision Tree visualization (Matplotlib)
     ![output](https://github.com/user-attachments/assets/8741d143-c3d3-4e87-85e8-4a717eb0b115)

     Interactive customer churn scatter plot (Plotly)
     
     ![newplot](https://github.com/user-attachments/assets/aa08ddf8-44d5-4a4b-a9b2-62b98cccfe5a)

   **Model Performance**: The Decision Tree model achieves an accuracy of ~`{accuracy:.2f}` (modify based on actual results).

4. ## Contributing
   Feel free to fork, create pull requests, and contribute!

