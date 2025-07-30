# 🔥 Algerian Forest Fire Prediction

A machine learning web application that predicts forest fire occurrence in Algeria using weather and environmental data.

## 🌟 Project Overview

This project uses Ridge Regression to predict forest fire risk based on meteorological and environmental factors. The model is deployed as a Flask web application with an intuitive user interface for real-time predictions.

## 🚀 Features

- **Machine Learning Model**: Ridge Regression for accurate fire risk prediction
- **Web Interface**: User-friendly Flask web application
- **Real-time Predictions**: Instant fire risk assessment
- **Data Processing**: Automated feature scaling and preprocessing
- **Responsive Design**: Works on desktop and mobile devices

## 📊 Dataset

The model is trained on Algerian forest fire data including:
- **Temperature**: Ambient temperature (°C)
- **RH**: Relative Humidity (%)
- **Ws**: Wind Speed (km/h)
- **Rain**: Rainfall (mm)
- **FFMC**: Fine Fuel Moisture Code
- **DMC**: Duff Moisture Code
- **ISI**: Initial Spread Index
- **Classes**: Fire/No Fire classification
- **Region**: Geographical region identifier

## 🛠️ Technologies Used

- **Backend**: Python, Flask
- **Machine Learning**: Scikit-learn, Ridge Regression
- **Data Processing**: Pandas, NumPy
- **Model Serialization**: Pickle
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Ready for cloud deployment

## 📁 Project Structure

```
Algerian_forest_fire/
├── applicayion.py                          # Main Flask application
├── requirements.txt                # Python dependencies
├── models/
│   ├── ridge.pkl                  # Trained Ridge Regression model
│   └── scaler.pkl                 # StandardScaler for feature scaling
├── templates/
│   ├── index.html                 # Home page
│   └── Home.html                  # Prediction results page
├── notebooks/
│   ├── Data_cleaning_EDA.ipynb    # Data cleaning and exploration
│   └── Model_building_forestfire.ipynb  # Model training and evaluation
└── README.md                      # Project documentation
```

## 🔧 Installation & Setup

### Prerequisites
- Python 3.7+
- pip package manager

## 📈 Model Performance

- **Algorithm**: Ridge Regression
- **Features**: 9 environmental and meteorological variables
- **Preprocessing**: StandardScaler for feature normalization
- **Evaluation**: Cross-validation and performance metrics detailed in notebooks

## 🔬 Data Science Workflow

1. **Data Collection**: Algerian forest fire historical data
2. **Data Cleaning**: Handling missing values and outliers
3. **Exploratory Data Analysis**: Understanding feature relationships
4. **Feature Engineering**: Creating relevant features for prediction
5. **Model Selection**: Comparing different algorithms
6. **Model Training**: Ridge Regression with hyperparameter tuning
7. **Model Evaluation**: Performance assessment and validation
8. **Deployment**: Flask web application development

## 📊 Key Insights

- Temperature and humidity are strong predictors of fire risk
- Wind speed significantly affects fire spread potential
- Seasonal patterns influence fire occurrence
- Regional variations in fire risk patterns
- FFMC and DMC indices are crucial for accurate predictions

## 🌐 Deployment

The application is ready for deployment on various platforms:
- **Heroku**: `Procfile` ready
- **AWS Elastic Beanstalk**: Compatible
- **Render**: Direct GitHub deployment
- **Railway**: Simple deployment process

## 📝 Future Enhancements

- [ ] Add real-time weather API integration
- [ ] Implement ensemble methods for better accuracy
- [ ] Create mobile app version
- [ ] Add geographical visualization
- [ ] Include historical fire data visualization
- [ ] Implement user authentication
- [ ] Add email/SMS alerts for high-risk predictions

---

⭐ **If you found this project helpful, please give it a star!** ⭐
