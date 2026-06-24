# ✈️ SkyFare · Intelligent Flight Price Prediction Engine

## 📊 Project Architecture
The project is structurally divided into an isolated full-stack architecture:
*   **Frontend**: A responsive web user interface built using React, Vite, and styled with Tailwind CSS.
*   **Backend**: A Python-based prediction engine utilizing Flask/FastAPI to serve predictions from a trained machine learning model (`.pkl`).
*   **Research & Core ML**: Comprehensive data analysis, feature engineering, and model training documented step-by-step inside a Jupyter Notebook.

---

## 🛠️ Tech Stack
*   **Frontend**: React.js, Vite, Tailwind CSS
*   **Backend**: Python, Flask / FastAPI
*   **Machine Learning**: Scikit-Learn, Pandas, NumPy, Jupyter Notebook

---

## 🚀 Installation & Running the Application

Follow the steps below to set up and run both the backend and frontend services locally.

### 1. Setting Up the Backend
Navigate to the root directory of your project where your backend files reside.

```bash
# Activate your virtual environment (if using myenv)
source myenv/Scripts/activate

# Install required dependencies
pip install -r requirements.txt

# Run the backend prediction server
python app.py
