# 🌍 Climate Data Analysis and Weather Prediction System

## 📌 Project Overview
This project focuses on analyzing climate and weather data to extract insights and build predictive models. It includes data collection, data preprocessing, visualization, and machine learning models to predict weather conditions such as rain, temperature, and air quality.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA) on weather data
- Identify patterns in temperature, humidity, and weather conditions
- Build machine learning models for prediction
- Predict:
  - Rain (Yes/No)
  - Weather condition (Clear, Clouds, Rain, etc.)
  - Air Quality Index (AQI)
  - Next-day Temperature

---

## 🧩 Project Phases

### 🟦 Phase 1: Data Collection and Preparation
- Collected weather data using API (JSON format)
- Converted JSON to structured dataset (CSV)
- Cleaned data and handled missing values

---

### 🟩 Phase 2: Exploratory Data Analysis (EDA)
- Visualized temperature trends across states and months
- Analyzed humidity and pressure impact on weather
- Identified seasonal patterns

---

### 🟨 Phase 3: Machine Learning Models

#### 🌧 Rain Prediction (Classification)
- Algorithm: Random Forest Classifier
- Features: Humidity, Pressure, Weather, City
- Output: Rain Tomorrow (Yes/No)

#### 🌦 Weather Prediction (Classification)
- Predicts weather condition based on temperature

#### 🌫 AQI Prediction
- Predicts air quality using weather features

#### 🌡 Temperature Prediction (Regression)
- Algorithm: Random Forest Regressor
- Predicts next-day temperature

---

## 📊 Model Performance
- Accuracy (Rain Model): ~ (add your value)
- Accuracy (Weather Model): ~ (add your value)
- MAE (Temperature Model): ~ (add your value)

---

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Statsmodels (optional)

---

## 📂 Dataset
- The dataset contains approximately 12 lakh (1.2 million) rows, making the file size too large to upload on GitHub.

📌 Kaggle Dataset Link: (https://www.kaggle.com/code/anshul3063/india-s-weather-2020-2021-data-analysis)

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Run all cells step-by-step

---

## 📁 Project Structure
├── data/
├── notebook/
├── src/
├── README.md
├── requirements.txt

---

## 📌 Conclusion

The project successfully demonstrates how machine learning can be used to analyze climate data and predict weather conditions, helping in better understanding of environmental patterns.

---

## 👨‍💻 Author

Krishna Yadav
