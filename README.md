# 04_Classify-Vehicles-Based-on-Engine-Emissions_202401100400014
🚗 Vehicle Emission Classification  This project aims to classify vehicles into emission categories (A, B, or C) based on features like engine size, fuel type, and CO₂ emissions. It uses a machine learning classification approach to predict the emission category of a vehicle.

## 📁 Dataset

The dataset contains:
- `engine_size`: Numeric value representing engine displacement
- `fuel_type`: Categorical (petrol, diesel, electric)
- `co2_emissions`: Numeric value in g/km
- `emission_category`: Target class (A, B, C)

## 🔧 Technologies Used

- Python
- pandas, numpy
- scikit-learn (RandomForestClassifier, LabelEncoder, StandardScaler)
- matplotlib, seaborn

## 🧠 Model Workflow

1. Data Preprocessing (encoding, scaling)
2. Train-Test Split
3. Model Training (Random Forest)
4. Evaluation (accuracy, precision, recall, F1-score)
5. Confusion Matrix Heatmap

## 📊 Results
Classification Report:
               precision    recall  f1-score  support
A              0.400000  0.400000  0.400000      5.0
B              0.250000  0.333333  0.285714      6.0
C              0.571429  0.444444  0.500000      9.0
accuracy       0.400000  0.400000  0.400000      0.4
macro avg      0.407143  0.392593  0.395238     20.0
weighted avg   0.432143  0.400000  0.410714     20.0


