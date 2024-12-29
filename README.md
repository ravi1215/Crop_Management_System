# Crop Recommendation & Yield Prediction System

This project consists of two main systems designed to help farmers and agricultural experts make data-driven decisions:

1. **Crop Recommendation System**: Suggests the best crops to grow based on environmental factors and soil conditions.
2. **Crop Yield Prediction System**: Predicts the yield of a crop based on various environmental and agricultural factors.

Both systems leverage machine learning models to provide recommendations and predictions based on the input data.

## Project Overview

The **Crop Recommendation System** uses various environmental and soil conditions (e.g., temperature, humidity, pH level, etc.) to recommend the most suitable crops for a given location.

The **Crop Yield Prediction System** uses environmental and agricultural data to predict the expected yield of a crop. This system utilizes regression models to estimate yields based on different conditions such as weather, irrigation, soil type, and more.

Both systems are packaged into one Flask web application, allowing easy interaction via a web interface.

## Technologies Used

- **Flask**: For creating the web application and API.
- **Scikit-learn**: For machine learning models for both recommendation and yield prediction.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Joblib**: For model serialization (saving and loading models).
- **Gunicorn**: For running the application in production.
- **HTML/CSS**: For designing the frontend of the web app.
- **Bootstrap**: For responsive layout and design.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/crop-recommendation-and-yield-prediction.git
   cd crop-recommendation-and-yield-prediction
   ```

2. Create and activate a virtual environment:
```bash
Copy code
python3 -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate     # For Windows
```

3. Install the required dependencies:
```bash
Copy code
pip install -r requirements.txt
```

4. Running the Application:
```bash
Copy code
python app.py
```
Access the application:
The application will be available at http://127.0.0.1:5000/ in your browser.

## Usage

Crop Recommendation:

Navigate to the crop recommendation page.
Enter the environmental conditions (e.g., temperature, humidity, etc.).
The system will recommend the best crop for the given conditions.

Crop Yield Prediction:

Navigate to the crop yield prediction page.
Enter the necessary environmental and agricultural data.
The system will predict the yield based on the provided data.
