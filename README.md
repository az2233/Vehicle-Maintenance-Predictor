# Vehicle Maintenance Predictor

**Data-Driven Approach for Automotive Embedded Systems**

## Project Overview
This project applies data science and machine learning techniques to improve vehicle maintenance. By analyzing sensor data from automotive embedded systems, the goal is to predict maintenance requirements and identify potential system failures before they occur.

---

## Project Structure
- **Data**  
- **Methodology**  
- **Usage**  
- **Results**  
- **Contributing**  

---

## Data
The dataset contains sensor readings from various automotive systems, including:

- Engine RPM  
- Fuel pressure  
- Lubrication oil pressure  
- Coolant pressure  
- Temperature readings  

The `Engine Condition` column is used as the target variable for predictive modeling.  
**Dataset source:** Engine-data

---

## Methodology
1. **Data Preprocessing:** Features are scaled using `RobustScaler` to reduce the influence of outliers.  
2. **Dimensionality Reduction:** `PCA` is applied to condense the data into principal components.  
3. **Anomaly Detection:** `Isolation Forest` is used to identify unusual sensor readings.  
4. **Predictive Modeling:** `RandomForestClassifier` predicts engine conditions.  
5. **Evaluation:** Model performance is assessed using precision, recall, and F1-score.

---

## Usage
Ensure you have Python 3.8+ installed along with the following packages:

- pandas  
- numpy  
- scikit-learn  
- matplotlib (optional for visualizations)  

Run the Jupyter Notebook in the following order:

1. `Predict_maint-checkpoint.ipynb`

---

## Results
The model achieved **72% accuracy**, with higher recall for detecting engine faults. Future improvements include refining anomaly detection and exploring additional machine learning algorithms for better performance.

---

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository  
2. Make your changes  
3. Submit a pull request  

---
