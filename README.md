# Used Car Price Prediction with Machine Learning

## Project Overview

This project aims to predict the prices of used cars based on various features such as car brand, fuel type, kilometers driven, and city of sale. The project utilizes machine learning techniques, particularly the Random Forest Regressor, to develop an accurate model for car price prediction.

## Dataset

The dataset used for this project includes various attributes related to used cars, such as:
- Car Name
- Car Price (in rupees)
- Kilometers Driven
- Fuel Type
- City of Sale

## Steps Involved

1. **Data Preprocessing:**
   - Extracted brand names from car names.
   - Cleaned and converted car price data to numerical values.
   - Processed kilometers driven data to remove unwanted characters and convert to integers.
   - Applied ordinal encoding to categorical variables.

2. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of car prices.
   - Checked for any anomalies or low price outliers in the data.

3. **Model Building:**
   - Split the dataset into training and test sets.
   - Implemented a `RandomForestRegressor` model.
   - Performed hyperparameter tuning using `GridSearchCV`.

4. **Model Evaluation:**
   - Evaluated the model using metrics such as MAE, MSE, RMSE, and R-squared.
   - Achieved significant improvements in predictive performance with the tuned model.

## Results

- **Mean Absolute Error (MAE):** 369,677.67 rupees
- **Mean Squared Error (MSE):** 548,991,998,676.93 rupees squared
- **Root Mean Squared Error (RMSE):** 740,939.94 rupees
- **R-squared (R2):** 0.64

The `RandomForestRegressor` model explained about 64% of the variance in car prices, significantly improving over the initial linear regression model.

## Future Work

- Further feature engineering to enhance model performance.
- Experimenting with additional models or ensemble methods.
- Continuous tuning of hyperparameters for better accuracy.

## Repository Structure

- `used_car_dataset.csv`: The dataset used for the project.
- `car_price_prediction.ipynb`: Jupyter notebook containing the code and analysis.
- `README.md`: Project overview and details.

## Getting Started

To get a local copy up and running follow these simple steps:

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username/used-car-price-prediction.git
**Contributing**
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

**Fork the Project**
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
**License**
Distributed under the MIT License. See LICENSE for more information.

**Contact**
Project Link: https://github.com/your_username/used-car-price-predictio
