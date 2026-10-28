# Early Forest Fire Prediction

An AI/ML-based project for predicting forest fire risk using weather and soil conditions, XGBoost, and satellite fire detections.

## Project Overview

This project combines machine learning predictions, live weather information, and satellite-based fire detections to visualize forest fire risk across monitored regions.

### Key Features

* Forest fire risk prediction using an XGBoost model.
* Weather and soil condition analysis.
* Interactive forest fire risk map.
* Satellite fire hotspot visualization using NASA FIRMS data.
* FastAPI backend and React frontend.
* Risk classification into Low, Medium, and High categories.

## Technologies Used

* Python
* XGBoost
* Pandas and NumPy
* FastAPI
* React
* Vite
* Open-Meteo API
* NASA FIRMS

## Project Structure

```text
early-fire-prediction/
├── backend/
├── frontend/
├── data_utils.py
├── train_xgboost.py
├── train_other_models.py
├── calibrate_thresholds.py
└── README.md
```

## Setup and Installation

### 1. Backend Setup

Open a terminal in the project directory and run:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows:

```powershell
venv\Scripts\activate
```

Install the backend dependencies:

```bash
pip install -r requirements.txt
```

Return to the project root:

```bash
cd ..
```

### 2. Train the Model

Install the training dependencies:

```bash
pip install -r requirements-training.txt
```

Place the required training datasets in their documented locations, then run:

```bash
python train_xgboost.py
python calibrate_thresholds.py
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
```

## Running the Project

### Start the Backend

From the backend directory, activate the virtual environment and run:

```bash
uvicorn main:app --reload
```

The backend should be available at:

`http://127.0.0.1:8000`

### Start the Frontend

From the frontend directory, run:

```bash
npm run dev
```

Open the local address displayed in the terminal, usually:

`http://localhost:5173`

## Model Evaluation

The project README reports the following evaluation results for the XGBoost model on held-out 2023 data:

* ROC AUC: 0.987
* PR AUC: 0.963

These results are based on the existing project evaluation and are not a guarantee of real-world prediction accuracy.

## Data Sources

* Open-Meteo for weather and environmental data.
* NASA FIRMS for satellite fire detections.

Live satellite data requires an appropriate NASA FIRMS API key. Without one, the project can use historical fire detections in replay mode.

## Limitations

* The model was trained using data from a particular geographical region.
* Predictions may not generalize to other regions.
* Live environmental data may differ from the training data.
* Model scores should be treated as indicative fire-risk estimates, not as guaranteed probabilities.

## Author

**Aditi Patil**

Third-Year B.Tech Student
Government College of Engineering, Karad