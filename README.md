# MediForecast Pro: Integrated Health Prediction Platform

## About the Project
A web-based Medical Condition Prediction System created using machine learning to predict multiple diseases, currently featuring Diabetes and Heart Disease prediction. It utilizes models trained on healthcare datasets and serves predictions through an interactive web interface.

## Features
- **Diabetes Prediction**: Input health metrics (like glucose level, blood pressure, BMI, etc.) to predict the likelihood of diabetes.
- **Heart Disease Prediction**: Input cardiac health parameters to assess heart disease risk.
- **Interactive UI**: Built with Streamlit for a responsive and easy-to-use interface.

## Tech Stack
- **Frontend/Backend**: [Streamlit](https://streamlit.io/)
- **Machine Learning**: `scikit-learn` for predictive modeling
- **Data Manipulation**: `pandas`, `numpy`
- **UI Components**: `streamlit-option-menu`

## Project Structure
- `appv2.py`: Main Streamlit application script containing the UI and prediction logic.
- `models/`: Directory containing the pre-trained machine learning models (`diabetes_model.sav`, `heart_disease_model.sav`).
- `Modal-generation-files/`: Jupyter Notebooks and datasets used for data exploration, model training, and exporting the `.sav` models.

## Installation & Setup

1. **Clone the repository** (if applicable) or navigate to the project directory:
   ```bash
   cd Diseases-prediction-app
   ```

2. **Install the dependencies**:
   Ensure you have Python installed, then run:
   ```bash
   pip install streamlit scikit-learn pandas numpy streamlit-option-menu
   ```

3. **Run the Application**:
   Launch the Streamlit app locally:
   ```bash
   streamlit run appv2.py
   ```

## Usage
1. Open the local URL provided by Streamlit in your web browser.
2. Use the sidebar to navigate between "Diabetes Prediction" and "Heart Disease Prediction".
3. Enter the required health parameters and click the "Predict" button to see the assessment results.
