# Sentiment Analysis End-to-End MLOps Project

## 🔹 Project Overview

This project is an **end-to-end sentiment analysis system** that classifies user-generated text (like YouTube comments, tweets, or reviews) into **Positive, Negative, or Neutral** sentiments.

It is built following **MLOps best practices** to ensure reproducibility, scalability, and deployment readiness. The project covers the full workflow: data collection, preprocessing, model building, evaluation, deployment, and continuous integration.

---

## 🔹 Key Features

- **Data Collection:** Efficiently collect and clean text data for sentiment analysis.
- **Data Preprocessing & EDA:** Tokenization, stopword removal, stemming/lemmatization, vectorization (TF-IDF, BOW), and exploratory analysis.
- **Model Development:** Baseline models with Logistic Regression, improvements using advanced feature engineering, handling imbalanced data, and hyperparameter tuning.
- **Ensemble & Stacking:** Combining multiple models for better performance.
- **ML Pipelines:** Fully modular pipeline using **DVC** for reproducibility.
- **Model Tracking:** Logging experiments and metrics using **MLflow**, including model registration.
- **API Deployment:** Flask API for serving predictions in real-time.
- **Browser Integration:** Optional Chrome plugin for quick sentiment predictions.
- **Containerization & CI/CD:** Dockerized deployment with automated CI/CD pipelines on **AWS**.

---

## 🔹 Project Structure

Sentiment-Analysis-MLops
├── data/ # Raw and processed datasets
├── notebooks/ # EDA and model training notebooks
├── src/ # Source code modules
│ ├── data_ingestion.py
│ ├── data_preprocessing.py
│ ├── train_model.py
│ ├── evaluate_model.py
│ ├── predict.py
│ └── utils.py
├── app.py # Flask API
├── Dockerfile # Container configuration
├── dvc.yaml # DVC pipeline file
├── params.yaml # Hyperparameters and config
├── requirements.txt
└── README.md

---

## 🔹 Workflow Overview

### 1️⃣ Data Collection

- Gathered datasets from YouTube, Twitter, and public reviews.
- Cleaned and normalized text for consistent processing.

### 2️⃣ Data Preprocessing & EDA

- Text tokenization, stopword removal, and lemmatization.
- Feature extraction using **Bag of Words (BOW)** and **TF-IDF**.
- Visualizations for class distribution, word clouds, and text length analysis.

### 3️⃣ Model Development

- Built a **baseline model** with Logistic Regression.
- Improved using feature engineering and handling imbalanced data.
- Hyperparameter tuning for optimized performance.
- Applied **stacking ensembles** to boost accuracy.

### 4️⃣ ML Pipelines

- Modular pipeline using **DVC** for reproducible workflows.
- Components for:
  - Data ingestion
  - Data preprocessing
  - Model training
  - Model evaluation & logging with MLflow
  - Model registration

### 5️⃣ Deployment

- Flask API to serve predictions with a `/predict` endpoint.
- Dockerized for easy deployment on local or cloud servers.
- Optional Chrome plugin for instant sentiment predictions.

### 6️⃣ CI/CD

- Automated testing, model retraining, and deployment pipelines using **GitHub Actions**.
- AWS integration for scalable deployment.

---

## 🔹 Contact & Links

Connect with me:

[![Kaggle](https://img.shields.io/badge/Kaggle-3232?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/raghavramani3232)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raghav-ramani-711b56256/)
[![Twitter](https://img.shields.io/badge/X-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/RamaniRagh763)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raghavramani2004@gmail.com)
