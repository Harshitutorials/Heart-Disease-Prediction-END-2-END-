# Heart Disease Prediction – End-to-End Project

This repository contains a complete **end-to-end machine learning pipeline** for predicting the likelihood of heart disease based on patient health records. The project covers data preprocessing, model training, evaluation, deployment as a web app, and containerization.

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Dataset](#dataset)
* [Project Workflow](#project-workflow)
* [Getting Started](#getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Environment Variables](#environment-variables)
  * [Run Locally](#run-locally)
* [Project Structure](#project-structure)
* [Model Training](#model-training)
* [Web Application](#web-application)
* [Docker Setup](#docker-setup)
* [Deployment](#deployment)
* [Results](#results)
* [Future Improvements](#future-improvements)
* [Contributing](#contributing)
* [License](#license)

---

## Overview

Heart disease is one of the leading causes of death globally. Early detection can save lives. This project demonstrates how **machine learning models** can be applied to predict heart disease risk using clinical and lifestyle features.

We built an **end-to-end ML system** that:

1. Preprocesses patient data
2. Trains classification models (Logistic Regression, Random Forest, XGBoost, etc.)
3. Evaluates performance (accuracy, precision, recall, F1, ROC-AUC)
4. Exposes the best model via a **FastAPI/Flask web app**
5. Deploys via **Docker & cloud hosting** (Heroku/Render/AWS)

---

## Features

* Data cleaning, preprocessing, and feature engineering
* Multiple ML models with hyperparameter tuning
* Model evaluation with detailed metrics and visualizations
* Persist trained model with **joblib/pickle**
* REST API for predictions
* Web UI with form inputs for patient details
* Dockerized deployment
* CI/CD-ready (GitHub Actions example)

---

## Tech Stack

**Core:** Python 3.10+

**Libraries:**

* Data: Pandas, NumPy, Scikit-learn
* Visualization: Matplotlib, Seaborn
* ML Models: scikit-learn, XGBoost
* API: Flask/FastAPI
* Frontend (UI): HTML, CSS, Bootstrap/Streamlit
* Deployment: Docker, Heroku/Render

---

## Dataset

We used the **UCI Heart Disease dataset** (Cleveland) or Kaggle’s *Heart Disease UCI* dataset.

* Features include age, sex, blood pressure, cholesterol, chest pain type, max heart rate, etc.
* Target: `1` → heart disease present, `0` → no heart disease

Dataset link: [https://www.kaggle.com/datasets/ronitf/heart-disease-uci](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)

---

## Project Workflow

1. Data Collection
2. Dat
