# 🌍 Earthquake Magnitude Prediction

![Earthquake Banner](https://www.usgs.gov/sites/default/files/images/22_0429_CA_GlobalEarthquakes_1200x675.jpg)

## 📊 Project Overview

This project implements machine learning techniques to predict earthquake magnitudes using historical seismic data. By leveraging advanced regression algorithms, we aim to develop accurate predictive models that could potentially contribute to early warning systems and risk assessment strategies.

### Key Features

- **Multiple ML Models**: Implementation and comparison of Linear Regression (LR), Support Vector Regression (SVR), and Random Forest Regression (RFR)
- **Comprehensive Analysis**: Detailed evaluation of model performance with visualizations
- **Data Preprocessing**: Robust handling of missing values and feature engineering
- **Easy Reproducibility**: Well-documented code with clear instructions

## 🔍 Motivation

Earthquakes are natural disasters that can cause significant damage and loss of life. Accurate prediction of earthquake magnitudes is crucial for:

- Developing effective early warning systems
- Improving disaster planning and response
- Enhancing risk assessment for vulnerable areas
- Advancing scientific understanding of seismic activity

## 📋 Dataset

The analysis is performed on the `Earthquake Data.csv` dataset which includes historical earthquake records with features such as:

- Geographical coordinates (latitude and longitude)
- Depth of the earthquake
- Time and date of occurrence
- Various seismic measurements
- Other relevant attributes

## 📈 Model Performance

After rigorous testing and evaluation, our comparative analysis revealed:

![Model Comparison](https://i.imgur.com/JNZqJdk.png)

**Key findings:**
- **Random Forest Regression (RFR)** demonstrated superior performance with the highest R² score and lowest error metrics
- **Support Vector Regression (SVR)** showed moderate predictive capability
- **Linear Regression (LR)** provided a useful baseline but was less effective for capturing the complex, non-linear relationships in seismic data

## 📊 Visualizations

### Feature Importance
![Feature Importance](https://i.imgur.com/qV2nFNh.png)

### Actual vs Predicted Magnitude
![Prediction Results](https://i.imgur.com/aEGX0De.png)

### Earthquake Distribution
![Earthquake Distribution Map](https://i.imgur.com/W7vKCgL.png)

### Error Distribution
![Error Distribution](https://i.imgur.com/VjZ9XqP.png)

## 🛠️ Technologies Used

- **Python** - Primary programming language
- **Pandas & NumPy** - Data manipulation and numerical computations
- **Scikit-learn** - Implementation of machine learning algorithms
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development and documentation

## 💻 Installation and Usage

### Prerequisites
- Python 3.7+
- Jupyter Notebook/Lab

### Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/Hari-Krishnan-N/EarthQuake-ML_Magnitude_Prediction_System.git
cd Earthquake-Magnitude-Prediction
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook model_comparision.ipynb
```

### Workflow

1. **Data Exploration & Preprocessing**:
   - Load and examine the dataset
   - Handle missing values
   - Feature engineering and selection

2. **Model Training & Evaluation**:
   - Split data into training and testing sets
   - Train multiple regression models
   - Evaluate performance using metrics like RMSE, MAE, and R²

3. **Results Analysis**:
   - Compare model performances
   - Visualize predictions and errors
   - Generate insights and conclusions

## 🔮 Future Enhancements

- Implement deep learning models for potentially improved accuracy
- Incorporate real-time data feeds for dynamic predictions
- Develop a web application for interactive visualization
- Extend the analysis to specific geographic regions
- Add time-series analysis for temporal patterns

## 👨‍💻 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- United States Geological Survey (USGS) for earthquake data
- The open-source community for providing essential libraries and tools
- Academic research that has advanced the field of earthquake prediction

---