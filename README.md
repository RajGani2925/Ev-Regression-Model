# 🚗 EV Adoption Forecasting in Washington State

## 📌 Project Overview
As electric vehicle (EV) adoption increases, governments and city planners must prepare for growing infrastructure needs—especially for EV charging stations. This project uses historical vehicle registration data from Washington State to forecast future EV adoption trends.

## 📊 Dataset
- **Source**: [Kaggle - Electric Vehicle Population Size (2024)](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024)
- **Duration**: January 2017 – February 2024
- **Features**:
  - `Date`: Month-end date of vehicle count
  - `County`: Location of registration
  - `Vehicle Primary Use`: Passenger or Truck
  - `BEVs`, `PHEVs`, `EV Total`, `Non-EV Total`
  - `Total Vehicles`, `Percent EVs`

## 🎯 Objective
Build a regression model that forecasts the number of electric vehicles (EVs) in upcoming years based on historical trends. This will:
- Predict future EV adoption rates
- Identify high-growth regions
- Support planning for charging infrastructure

## 🧠 Methodology
1. **Data Cleaning**: Handle missing values and aggregate monthly data
2. **Exploratory Data Analysis (EDA)**: Visualize trends and regional adoption
3. **Feature Engineering**: Add time-based and ratio-based features
4. **Modeling**: Use regression models (Linear Regression, Random Forest, etc.)
5. **Evaluation**: Compare model performance using metrics like RMSE
6. **Forecasting**: Generate future EV registration projections

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Example Output
- Graphs showing EV growth over time
- Forecasted EV counts by county
- Heatmaps of high-adoption regions

## 🔍 Use Cases
- Urban infrastructure planning
- Policy design and emissions tracking
- Energy and utility planning

## 📁 Project Structure

