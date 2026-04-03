# 🌱 Crop Recommendation System using Machine Learning

A machine learning project that predicts the **most suitable crop to grow** based on soil nutrients and environmental conditions such as temperature, humidity, rainfall, and soil pH.

This project uses a **Gradient Boosting Classifier** trained on agricultural data to provide crop recommendations.

---

# 📊 Dataset

Dataset used: **Crop Recommendation Dataset**

Features used for prediction:

| Feature | Description |
|-------|-------------|
| N | Nitrogen ratio in soil |
| P | Phosphorous ratio in soil |
| K | Potassium ratio in soil |
| temperature | Temperature in °C |
| humidity | Relative humidity (%) |
| ph | Soil pH value |
| rainfall | Rainfall in mm |

Target variable:

```
label → crop type
```

Examples of crops:

```
Rice
Maize
Cotton
Coffee
Mango
Chickpea
Kidney Beans
```

---

# ⚙️ Machine Learning Pipeline

The project follows a complete ML workflow:

```
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
```

---

# 🧠 Model Used

**Gradient Boosting Classifier**

Why Gradient Boosting?

- Handles nonlinear relationships well
- Works efficiently on tabular data
- Strong performance in classification tasks

Hyperparameters used:

```
n_estimators = 300
learning_rate = 0.1
max_depth = 3
```

---

# 📈 Model Performance

Evaluation metrics used:

- Accuracy
- Classification Report
- Confusion Matrix
- Cross Validation

Typical results:

```
Accuracy: ~96% – 99%
```

Cross-validation:

```
Mean CV Accuracy ≈ 0.97
```

---

# 📊 Feature Importance

The model analyzes which factors influence crop recommendation the most.

Example important features:

```
Rainfall
Nitrogen
Humidity
Temperature
pH
```

These features align with real agricultural research where soil nutrients and climate strongly influence crop suitability.

---

# 💾 Model Saving

The trained model is saved using **Joblib** for reuse without retraining.

```
crop_recommendation_model.pkl
```

This allows the model to be easily deployed in:

- Web applications
- APIs
- Agricultural advisory systems

---

# 🔮 Example Prediction

Input:

```
N = 90
P = 42
K = 43
temperature = 23
humidity = 82
ph = 6.5
rainfall = 200
```

Prediction:

```
Recommended Crop → Rice
```

---

# 🛠️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/crop-recommendation-ml.git
```

Install dependencies:

```
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Run the training script:

```
python crop_model.py
```

The script will:

- Train the model
- Evaluate performance
- Generate visualizations
- Save the trained model


---

# 🌍 Applications

This system can be used in:

- Precision agriculture
- Smart farming systems
- Agricultural advisory platforms
- IoT-based soil monitoring systems



**Rounak**

Machine Learning | Data Analytics | AI Applications in Agriculture
