# SCT_ML_1

# House Price Prediction using Linear Regression

In this project I have implemented a simple **linear regression model** to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

---

## 📌 Objective

To build a linear regression model that predicts the sale price of houses using:
- **Living area (in square feet)** (`GrLivArea`)
- **Number of bedrooms above ground** (`BedroomAbvGr`)
- **Number of full bathrooms** (`FullBath`)

---

## Dataset

- Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- File used: `train.csv`
- Total samples: 1460 rows

---

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Workflow

1. **Data Preprocessing**
   - Selected relevant features
   - Handled missing values
   - Split into training and test sets

2. **Model Training**
   - Trained a `LinearRegression` model on the training data

3. **Evaluation**
   - Calculated Mean Squared Error (MSE)
   - Visualized Actual vs Predicted Prices

---

## Sample Output

<img src="https://github.com/dharan0808/SCT_ML_1/blob/main/actual_vs_predicted.png" width="500">

---

## 📁 Project Structure

SCT_ML_1/
├── data/
│ └── train.csv
├── linear_regression_house_price.ipynb
├── README.md
└── venv

---

## 📈 Results

- The model was able to capture the general trend in housing prices.



