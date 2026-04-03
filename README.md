# Crop Recommendation System
A machine learning project that predicts the most suitable crop to grow based on soil nutrients and environmental conditions such as temperature, humidity, rainfall, and soil pH.

This project uses a Gradient Boosting Classifier trained on agricultural data to provide crop recommendations.

📊 Dataset

Dataset used: Crop Recommendation Dataset

Features used for prediction:

Feature	Description
N	Nitrogen ratio in soil
P	Phosphorous ratio in soil
K	Potassium ratio in soil
temperature	Temperature in °C
humidity	Relative humidity (%)
ph	Soil pH value
rainfall	Rainfall in mm

Target variable:

label → crop type

Examples of crops:

Rice
Maize
Cotton
Coffee
Mango
Chickpea
Kidney Beans
⚙️ Machine Learning Pipeline

The project follows a complete ML workflow:

Data Loading
↓
Data Exploration
↓
Label Encoding
↓
Feature Scaling
↓
Train-Test Split
↓
Model Training (Gradient Boosting)
↓
Model Evaluation
↓
Cross Validation
↓
Feature Importance Analysis
↓
Model Serialization (.pkl)
🧠 Model Used

Gradient Boosting Classifier

Why Gradient Boosting?

Handles nonlinear relationships well
Works efficiently on tabular data
Strong performance in classification tasks

Hyperparameters used:

n_estimators = 300
learning_rate = 0.1
max_depth = 3
📈 Model Performance

Evaluation metrics used:

Accuracy
Classification Report
Confusion Matrix
Cross Validation

📊 Feature Importance

The model analyzes which factors influence crop recommendation the most.

Example important features:

Rainfall
Nitrogen
Humidity
Temperature
pH
🌍 Applications

This system can be used in:

Precision agriculture
Smart farming systems
Agricultural advisory platforms
IoT-based soil monitoring systems
