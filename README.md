# AI-Based Student Academic Performance Prediction System

A Streamlit application that estimates a student's final academic score from academic and attendance indicators using a trained machine-learning model.

## Live Demo

[Open ScholarIQ — Student Performance Prediction](https://suman-tech.streamlit.app/)

> The demo URL is the Streamlit address supplied for this project. App availability should be checked in Streamlit Community Cloud.

## Features

- Student profile and academic input form
- Attendance percentage calculation
- Machine-learning-based final score estimate
- Grade and performance summary
- Visual performance breakdown
- Personalized study recommendations
- Downloadable student report

## Technology Stack

- Python
- Streamlit
- Pandas and NumPy
- Scikit-learn and Joblib
- Plotly

## Project Structure

```text
Dataset/
Notebook/
Model/
  student_model.pkl
Streamlit_App/
  app.py
  style.css
README.md
requirements.txt
```

## Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/ShivamkumarsumanDAengineer/AI-Based-Student-Academic-Performance-Prediction-System.git
   cd AI-Based-Student-Academic-Performance-Prediction-System
   ```

2. Create and activate a virtual environment, then install dependencies:
   ```bash
   python -m venv .venv
   # Windows PowerShell
   .\.venv\Scripts\Activate.ps1
   python -m pip install -r requirements.txt
   ```

3. Start the Streamlit app:
   ```bash
   streamlit run Streamlit_App/app.py
   ```

The trained model is expected at `Model/student_model.pkl`. The Streamlit entry point is `Streamlit_App/app.py`.

## Deploy with Streamlit Community Cloud

Create or manage the app in [Streamlit Community Cloud](https://share.streamlit.io/) and select:

- **Repository:** `ShivamkumarsumanDAengineer/AI-Based-Student-Academic-Performance-Prediction-System`
- **Branch:** `main`
- **Main file path:** `Streamlit_App/app.py`

The app uses the repository's root `requirements.txt`.

## Machine Learning Models

The project documentation lists Linear Regression, Random Forest, and XGBoost as explored models. The deployed interface loads the saved estimator from `Model/student_model.pkl`.
