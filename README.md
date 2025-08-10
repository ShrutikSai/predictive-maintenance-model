# Predictive Maintenance for Industrial Equipment (Simulated/Sensor Data)

This project focuses on building predictive maintenance models to classify equipment failure types using sensor data from industrial machinery.

## Dataset

The dataset contains simulated sensor readings such as temperature, torque, rotational speed, and tool wear, labeled with failure types.

Access the dataset here:  
[Machine Predictive Maintenance Classification - Kaggle](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification/code?datasetId=1697740&sortBy=voteCount)

## Highlights

- Data cleaning and temperature conversion from Kelvin to Celsius  
- Visualization of sensor data distributions and failure types  
- Encoding categorical variables and splitting data for training/testing  
- Model training and evaluation using accuracy, classification report, and confusion matrix  
- Comparison of multiple ML algorithms with high precision results  

## Technologies Used

- Python, Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- category_encoders

## Results

| Model               | Training Accuracy | Test Accuracy |
|---------------------|-------------------|---------------|
| Decision Tree       | 100%              | 99.65%        |
| Random Forest       | 100%              | 99.35%        |
| Support Vector Machine | 96.73%          | 96.25%        |
| Logistic Regression | 96.64%            | 96.05%        |


---

Feel free to explore and adapt the code for predictive maintenance use cases.
