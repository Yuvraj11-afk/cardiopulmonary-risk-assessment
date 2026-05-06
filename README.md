# Cardiopulmonary Risk Assessment System

An AI-powered full-stack healthcare application designed for cardiopulmonary disease risk assessment using deep learning techniques.

The system analyzes:
- ECG images for heart-related abnormalities
- Lung medical images for pulmonary disease prediction

The project combines machine learning models with a modern web application interface using FastAPI and React.

---

# Features

## Heart Disease Prediction
- ECG image upload
- AI-based ECG analysis
- Deep learning prediction pipeline

## Lung Disease Detection
- Lung image upload
- CNN-based prediction system
- Medical image preprocessing

## Full Stack Integration
- FastAPI backend APIs
- React + Vite frontend
- Real-time communication between frontend and backend

## User Interface
- Interactive upload system
- Prediction visualization
- Modern responsive design

---

# Tech Stack

## Frontend
- React
- Vite
- JavaScript
- CSS

## Backend
- FastAPI
- Python
- Uvicorn

## Machine Learning
- TensorFlow
- PyTorch
- OpenCV
- Grad-CAM
- Scikit-learn

---

# Project Structure

```bash
cardiopulmonary-risk-assessment/
│
├── cardiopulmonary-backend/
│   ├── routers/
│   ├── main.py
│   ├── requirements.txt
│   └── .gitignore
│
├── cardiopulmonary-ui/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── Model_Training/
│   ├── Heart/
│   └── Lung/
│
├── .gitignore
└── README.md
```

---

# Installation and Setup

## Clone Repository

```bash
git clone https://github.com/your-username/cardiopulmonary-risk-assessment.git

cd cardiopulmonary-risk-assessment
```

---

# Backend Setup

## Navigate to backend

```bash
cd cardiopulmonary-backend
```

## Create virtual environment

```bash
python -m venv venv
```

## Activate virtual environment

### Windows

```bash
venv\Scripts\activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run backend server

```bash
uvicorn main:app --reload
```

Backend will run at:

```bash
http://127.0.0.1:8000
```

---

# Frontend Setup

## Navigate to frontend

```bash
cd cardiopulmonary-ui
```

## Install dependencies

```bash
npm install
```

## Start frontend server

```bash
npm run dev
```

Frontend will run at:

```bash
http://localhost:5173
```

---

# Machine Learning Models

The project includes:
- ECG classification models
- Lung disease detection models
- TensorFlow and PyTorch implementations
- Model training notebooks and experiments

---

## Model Files

Due to GitHub file size limitations, trained deep learning model weights are not stored directly in this repository.

Download all trained models from Google Drive:

https://drive.google.com/drive/folders/1DaoDABsMJ34tX_QFpQ0SxE9nAp47TBK_?usp=sharing

  ---

# Future Improvements

- Authentication system
- Database integration
- Cloud deployment
- Docker support
- Advanced explainability features
- Improved prediction accuracy
- Patient report generation

---

# Author

Yuvraj Bhardwaj

---

# License

This project is for educational and research purposes.