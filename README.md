# 🏡 House Price Prediction using Linear Regression

## 📌 Project Overview
This is a beginner-friendly machine learning project that demonstrates how a **Linear Regression model** learns from data and makes predictions.

The model uses a simple dataset with:
- **Input (Feature):** Area  
- **Output (Target):** Price  

This project helps beginners understand:
- How linear regression works  
- How models learn patterns from data  
- How to visualize data and predictions  

---

## 📂 Project Structure
  ├── .gitignore ( ignoring virtual environment)
  
  ├── area.csv ( actual data)
  
  ├── input_data.csv (unseen data for predictions)
  
  ├── linear_regression.ipynb
  
  ├── predicted_house_prices (unseen data with its predictions)
  
  ├── requirements.txt (all dependencies)


---

## 📊 Dataset Description

- `area.csv` → Training data (Area vs Price)  
- `input_data.csv` → New input values for prediction  

---

- Install all dependencies using pip install
- Import all libraries required

## Why Linear regression

<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/13416ed0-118e-4094-ada2-17279ae76132" />

The graph shows a positive linear relationship between area and price.
- As the area increases, the price also increases.

The data points follow an upward trend, which indicates that:
- Larger houses tend to have higher prices
- The relationship is approximately linear (good for Linear Regression)

There is no major fluctuation or outliers, meaning:
- The data is clean
- The model can learn patterns effectively

Between 3000 and 3600 sqft, the price increases more sharply:
- This suggests a slightly stronger impact of area in that range

---

## ⚙️ Model Used

### Linear Regression

Linear Regression finds the relationship between input and output using:

y = mx + b

Where:
- `y` → Predicted Price  
- `x` → Area  
- `m` → Slope (Coefficient) - Indicates how much the price increases per unit increase in area  
- `b` → Intercept  

---

## Model training
- Train the model on the given **area.csv** data
  
## Model Predictions
- For model predictons use unseen **input_data.csv** data

---

## 📊 Model Predictions vs Actual Values

<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/f3ceda7c-b2bd-46bc-b5b7-6ceb2e88e49f" />

- Red line → Actual house prices (original dataset)
- Blue line → Predicted prices from the Linear Regression model

The blue predicted values closely follow the red actual values, indicating:
- The model has learned the relationship between area and price effectively

Most predicted points lie very close to the original data points, which means:
- The model has low error
- Predictions are reasonably accurate

The overall trend of both lines is consistently increasing, which means:
- Strong positive correlation between area and price

## Technologies used:

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-Learn
