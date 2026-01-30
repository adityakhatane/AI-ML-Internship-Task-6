# AI-ML Internship – Task 6  
## Linear Regression – House Price Prediction

---

## 📌 Objective  
The objective of this task is to build a **Linear Regression model** for predicting house prices and evaluate its performance using regression evaluation metrics.

---

## 📂 Dataset  
**California Housing Dataset** (from `sklearn`)

- Contains numerical features related to housing
- Target variable: `MedHouseValue` (continuous)

---

## 🛠 Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Steps Performed

### 1. Dataset Loading  
- Loaded the California Housing dataset using `fetch_california_housing`
- Converted the dataset into a Pandas DataFrame

---

### 2. Data Inspection  
- Checked dataset structure and summary statistics
- Verified numerical features and target variable

---

### 3. Feature and Target Separation  
- Features (`X`) selected from dataset
- Target (`y`) set as median house value

---

### 4. Train–Test Split  
- Split dataset into training and testing sets
- 80% data used for training and 20% for testing
- Ensured reproducibility using `random_state`

---

### 5. Model Training  
- Trained a **Linear Regression** model using training data

---

### 6. Prediction  
- Generated predictions on test data
- Compared predicted values with actual values

---

### 7. Model Evaluation  
The model was evaluated using:

- **Mean Absolute Error (MAE)**  
  Measures average absolute prediction error

- **Root Mean Squared Error (RMSE)**  
  Penalizes large errors and reflects prediction accuracy

---

### 8. Visualization  
- Plotted **Predicted vs Actual House Prices**
- Scatter plot used to visually assess model performance

---

### 9. Model Interpretation  
- Analyzed model coefficients
- Identified features with higher influence on house prices

---

## 📦 Deliverables  
- ✔ Jupyter Notebook (.ipynb)  
- ✔ MAE and RMSE evaluation report  
- ✔ Predicted vs Actual scatter plot  

---

## 🎯 Final Outcome  

The intern successfully built a complete **Regression model**, evaluated it using **MAE and RMSE**, visualized predictions, and interpreted model performance and feature importance.

---

## 📁 Repository Structure
