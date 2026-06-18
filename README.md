# 🚀 Bitcoin Price Forecasting using Seq2Seq LSTM

Final Project of **Dicoding - Membangun Proyek Deep Learning Tingkat Mahir**

## 📌 Overview

This project implements a **multivariate multi-step time series forecasting model** to predict Bitcoin closing prices using hourly historical cryptocurrency data.

The model leverages an advanced **Sequence-to-Sequence (Seq2Seq) LSTM architecture** built with TensorFlow and incorporates a customized training pipeline using GradientTape and custom callbacks.

---

## 🎯 Objectives

* Predict Bitcoin closing prices for multiple future time steps.
* Perform multivariate time series forecasting.
* Implement Seq2Seq LSTM architecture using TensorFlow Functional API.
* Utilize teacher forcing and auto-regressive inference.
* Develop a custom training loop and callback for enhanced flexibility.

---

## 📊 Dataset

The dataset contains hourly Bitcoin market data with the following features:

* Open
* High
* Low
* Close
* Volume

### Target Variable

* Close price of Bitcoin

---

## 🧠 Model Architecture

### Baseline Model

* LSTM
* Dense Layer

### Seq2Seq Model

* Encoder LSTM
* RepeatVector
* Decoder LSTM
* Dense Output Layer

### Advanced Techniques

* Teacher Forcing
* Auto-Regressive Inference
* Functional API
* Custom Training Loop using tf.GradientTape

---

## ⚙️ Training Pipeline

### Data Preprocessing

* Missing value handling
* Feature scaling
* Sliding window generation

### Training

* Custom Loss Function
* Custom Callback
* Custom Training Loop
* EarlyStopping
* ModelCheckpoint

---

## 📈 Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

Visualization:

* Actual vs Prediction Plot
* Forecast Results

---

## 📂 Project Structure

```text
.
├── Andi_Setiawan_Submission_Akhir_DLTM.ipynb
├── best_model_seq2seq_LSTM.keras
├── model_baseline_LSTM.keras
├── model_seq2seq_LSTM.keras
├── requirements.txt
└── README.md
```

---

## 🛠️ Libraries

* TensorFlow
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## 🌟 Features

✅ Multivariate Time Series Forecasting

✅ Multi-Step Forecasting

✅ Sequence-to-Sequence LSTM

✅ Teacher Forcing

✅ Auto-Regressive Inference

✅ TensorFlow Functional API

✅ Custom Callback

✅ Custom Training Loop using GradientTape

---

## 🎓 Course Information

**Dicoding Indonesia**

Course:

**Membangun Proyek Deep Learning Tingkat Mahir**

Project Type:

**Multivariate Multi-Step Time Series Forecasting**

---

## 👨‍💻 Author

**Andi Setiawan**

Politeknik Negeri Lampung

Machine Learning Enthusiast | Cloud Computing | Networking | Cyber Security

GitHub: https://github.com/andisetiawann
