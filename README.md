# House Price Prediction

This project builds a **House Price Prediction** model using **Linear Regression** and **Polynomial Regression** techniques.  
The dataset contains house sale prices for King County, USA (including Seattle), covering homes sold between May 2014 and May 2015.

---

## 📂 Dataset

- **Source**: [Kaggle - House Sales in King County](https://www.kaggle.com/harlfoxem/housesalesprediction)
- **Features include**:
  - `id`: Unique house ID
  - `date`: Date of house sale
  - `price`: Sale price
  - `bedrooms`, `bathrooms`, `sqft_living`, `floors`, etc.

---

## 🚀 Project Workflow

1. **Import Libraries**  
   - `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`

2. **Load and Explore the Data**  
   - Summary statistics, missing values, data types.

3. **Data Wrangling**  
   - Handling missing values, feature selection.

4. **Exploratory Data Analysis (EDA)**  
   - Visualization of relationships (e.g., `price` vs. `sqft_living`, `price` vs. `grade`, etc.)

5. **Model Development**
   - Simple Linear Regression
   - Multiple Linear Regression
   - Polynomial Regression
   - Pipelines for scaling and transforming features

6. **Model Evaluation**
   - R-squared
   - Mean Squared Error (MSE)

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📈 Results

- Built regression models to predict house prices.
- Evaluated model performance using R² score and visualizations.
- Polynomial Regression improved model accuracy compared to simple linear models.

---

## 📋 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/House_Price_Prediction.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook House_Price_Prediction.ipynb
   ```
3. Install required packages if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

---


## 🙌 Acknowledgements

- Dataset: [Kaggle - House Sales in King County, USA](https://www.kaggle.com/harlfoxem/housesalesprediction)
- Inspired by real estate price prediction projects.

---
## AUTHOR:
Muhammad Abdullah Wali
