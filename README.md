# Walmart Sales Prediction

This repository contains a machine learning project focused on predicting Walmart weekly sales using historical retail data. The project demonstrates data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model persistence.

---

## Project Structure

```
Walmart-Sales-Predict/
│
├── Walmart.csv
├── Walmart_Sales.ipynb
├── Walmart_sales_model.pkl
└── README.md
```

---

## Dataset Description

The dataset includes historical weekly sales data from Walmart stores.

**Key Features:**
- `Store` – Store ID
- `Dept` – Department ID
- `Date` – Week date
- `Weekly_Sales` – Sales for the week
- `IsHoliday` – Holiday indicator

---

## Objective

To build a regression model that accurately predicts weekly sales based on historical trends and store-level information.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Naman0911/Walmart-Sales-Predict.git
cd Walmart-Sales-Predict
```

### 2. Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

### 3. Run the Notebook
```bash
jupyter notebook Walmart_Sales.ipynb
```

---

## Using the Trained Model

```python
import joblib

model = joblib.load("Walmart_sales_model.pkl")
prediction = model.predict(X_new)
```

---

## Results

The notebook contains model evaluation metrics and visualizations that demonstrate the effectiveness of the trained regression model.

---

## Author

**Naman Upadhyay**

---

## License

This project is open for educational and learning purposes.
