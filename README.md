# 🚗 Electric Vehicle (EV) Adoption Forecasting

This project presents a machine learning-based approach to forecast electric vehicle (EV) adoption across counties using historical registration data. The objective is to understand and predict future trends in EV usage to support sustainable planning and EV infrastructure development.

---

## 📁 Project Structure

```plaintext
EV-Adoption-Forecasting/
├── EV_Adoption_Forecasting.ipynb              # Main notebook with data analysis and model
├── Electric_Vehicle_Population_By_County.csv  # Original raw dataset
├── preprocessed_ev_data.csv                   # Cleaned and processed dataset
├── forecasting_ev_model.pkl                   # Trained machine learning model
└── README.md                                  # Project overview and instructions
```

---

## 📊 Dataset Overview

- **Source**: Publicly available Electric Vehicle Population dataset  
- **Format**: CSV  
- **Fields include**:
  - `County`
  - `Make`, `Model`
  - `Electric Vehicle Type`
  - `Model Year`
  - `CAFV Eligibility`
  - `Vehicle Location` (aggregated)

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Cleaned and filtered raw data
- Grouped by county and year
- Extracted meaningful features for forecasting

### 2. Feature Engineering
- Aggregated EV counts per year per county
- Created time-series compatible structure
- Normalized and encoded necessary fields

### 3. Model Training
- Built regression model to predict future EV adoption
- Applied machine learning using Scikit-learn
- Saved trained model as a `.pkl` file

### 4. Model Evaluation
- Evaluated model using:
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared actual vs predicted EV counts

---

## 📈 Results

- Forecasted county-level EV adoption trends with reasonable accuracy
- Visualization of results shows realistic future projections
- The model generalizes well across different counties

---

## 🛠 Technologies Used

- Python 3
- Pandas and NumPy for data processing
- Matplotlib and Seaborn for visualization
- Scikit-learn for model building and evaluation
- Jupyter Notebook for interactive development

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Open `EV_Adoption_Forecasting.ipynb` in Jupyter Notebook.
3. Run all cells in sequence:
   - Load and preprocess data
   - Train the model
   - Evaluate results
4. The trained model can be loaded from `forecasting_ev_model.pkl` for reuse.

---

## 🔮 Future Improvements

- Include external features such as:
  - Fuel prices
  - Charging station density
  - Policy changes or incentives
- Use advanced forecasting models (e.g., ARIMA, LSTM)
- Deploy as a web-based dashboard for real-time forecasts
