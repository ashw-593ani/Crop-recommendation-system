# Crop Recommendation System

This project predicts the **most suitable crop** to grow based on soil, weather, and environmental conditions using **Machine Learning**.

## Live Demo
The app is hosted and can be accessed here:  
[Crop Recommendation System](https://crop-recommendation-system-mzwc.vercel.app/)

## Features
The system recommends crops based on the following input features:

| Feature           | Description                                           | Example         |
|------------------|-------------------------------------------------------|----------------|
| Nitrogen (N)      | Nitrogen content in the soil (in kg/ha)             | 90             |
| Phosphorus (P)    | Phosphorus content in the soil (in kg/ha)           | 42             |
| Potassium (K)     | Potassium content in the soil (in kg/ha)            | 43             |
| Temperature       | Average temperature (°C)                             | 30             |
| Humidity          | Average humidity (%)                                  | 70             |
| pH                | Soil pH level                                        | 6.5            |
| Rainfall          | Average rainfall (mm)                                | 200            |

## Technologies Used
- **Python** – Programming language  
- **Flask** – Web framework for the API  
- **Scikit-learn** – Machine Learning library  
- **Pandas / NumPy** – Data analysis and manipulation  

## Setup Instructions

### 1. Clone the repository
```bash
git clone <repo-url>
cd <repository-folder>

# 2. Create a virtual environment (recommended)
python -m venv myenv

# Activate the environment:

# Windows:

myenv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt
# 4. Run the Flask app locally
python app.py
# 5. Access the app

# Locally: http://127.0.0.1:5000/

# Hosted on Render: https://crop-recommendation-system-s6wd.onrender.com

# 6. Make Recommendations

# Fill in the soil and weather details (N, P, K, Temperature, Humidity, pH, Rainfall).

# Click Predict./

# The system will recommend the most suitable crop for cultivation.

# File Structure
├── app.py             # Flask application
├── model.pkl          # Trained ML model
├── requirements.txt   # Required Python packages
├── templates/         # HTML templates for the Flask app
└── README.md
# Notes

# Ensure Python version is 3.10.10

# Input values should match the expected format (numeric for N, P, K, Temperature, Humidity, pH, Rainfall).

# The model is trained on historical crop data for accurate recommendations.


---
