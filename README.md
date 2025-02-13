# Delhi House Price Prediction

## Overview
This project aims to predict house prices in Delhi using machine learning techniques. The dataset used for training and evaluation is sourced from MagicBricks, containing various housing attributes such as location, size, price, and other relevant features.

## Technologies Used
- **Python** (Data processing and modeling)
- **Jupyter Notebook** (Development environment)
- **Pandas** (Data manipulation)
- **NumPy** (Numerical computations)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-Learn** (Machine Learning models)

## Models Implemented
1. **Decision Tree Regressor**
   - Training Score: **0.9904**
2. **Random Forest Regressor**
   - Training Score: **0.9642**
   - **R² Score on Test Set:** **0.8439**

## Dataset Information
- The dataset consists of real estate listings from MagicBricks.
- Features include property size, location, price, number of rooms, and other relevant details.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/kusadit/House-Prediction-.git
   cd House-Prediction-
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook mian.ipynb
   ```

## Results & Insights
- The **Random Forest Regressor** performed well with an **R² score of 0.8439**, indicating a good level of predictive accuracy.
- Decision Tree Regressor had a high training score, suggesting potential overfitting.
- Feature importance analysis can help refine the model further.
