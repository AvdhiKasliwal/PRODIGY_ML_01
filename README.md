# PRODIGY_ML_01  
## House Price Prediction using Linear Regression

### 📌 Task Description
The objective of this task is to implement a **Linear Regression model** to predict house prices based on:
- Square footage
- Number of bedrooms
- Number of bathrooms

This task is completed as part of the **Machine Learning Internship** at Prodigy Infotech.

---

### 📂 Dataset Information
- Dataset Name: House Prices – Advanced Regression Techniques
- Source: Kaggle
- Link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
- File Used: `train.csv`

---

### 🛠️ Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

### 📊 Features Used
**Input Features:**
- `GrLivArea` – Above-ground living area (square feet)
- `TotalBsmtSF` – Total basement area
- `BedroomAbvGr` – Number of bedrooms
- `FullBath` – Number of full bathrooms
- `HalfBath` – Number of half bathrooms

**Target Variable:**
- `SalePrice` – House price

---

### ⚙️ Methodology
1. Loaded dataset using Pandas
2. Selected relevant features
3. Handled missing values
4. Split data into training and testing sets
5. Trained a Linear Regression model
6. Evaluated the model using R², MAE, and RMSE
7. Visualized actual vs predicted prices

---

### 📈 Evaluation Metrics
- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

---

### ▶️ How to Run the Project

This project was implemented using Google Colab.
Steps to run:

Open the notebook file house_price_prediction.ipynb in Google Colab

Upload the dataset file train.csv when prompted (or keep it in the same directory)

Run all cells sequentially to train the model and view results

Alternatively, you can open the notebook directly from GitHub using Colab:

Open Google Colab

Click File → Open notebook → GitHub

Paste the repository link and select house_price_prediction.ipynb
