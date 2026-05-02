## 🛠️ Tech Stack
* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 📊 The Pipeline
The workflow in `SalaryPrediction.ipynb` includes:
1. **Data Preprocessing:** - Handling missing values and outliers.
   - **Scaling:** Using `StandardScaler` to normalize numerical data.
   - **Encoding:** Implementing `OneHotEncoder` for nominal variables and `OrdinalEncoder` for categorical hierarchies (e.g., Education Level).
2. **Feature Engineering:** Using `ColumnTransformer` to create a streamlined transformation pipeline.
3. **Model Selection:**
   - **Linear Regression:** As a baseline model.
   - **Random Forest Regressor:** An ensemble method to capture non-linear relationships.
4. **Evaluation:** Assessing performance using R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## 🚀 Key Features
- **Scalability:** Built to handle large-scale datasets (250k+ entries).
- **Robustness:** Integrated preprocessing prevents data leakage and ensures consistent feature scaling.
- **Comparison:** Provides a side-by-side performance evaluation of different regression algorithms.

## 📁 Repository Structure
- `SalaryPrediction.ipynb`: The primary notebook containing all analysis and modeling code.
- `README.md`: Project documentation.

## 📈 Future Scope
- Implementation of hyperparameter tuning using `GridSearchCV`.
- Developing a web interface using **Streamlit** for real-time salary estimation.
- Incorporating deeper analysis into the impact of remote work on global pay scales
