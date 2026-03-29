# -STFT--CNN-Stock-Prediction
# 📊 Stock Price Prediction using STFT and CNN
NAME : AMRUTHA K S
TCR24CS011

## 📌 Overview
This project explores how signal processing and deep learning can be combined to predict stock prices. Financial time series data is transformed into a time-frequency representation using Short-Time Fourier Transform (STFT), and a Convolutional Neural Network (CNN) is used for prediction.

---

## 🎯 Objective
- Treat financial data as a signal
- Convert time-domain data into frequency domain
- Generate spectrograms using STFT
- Use CNN to learn patterns and predict future values

---

## 🔁 Methodology

### 1. Data Representation
Financial data is treated as a time series signal.

### 2. STFT (Short-Time Fourier Transform)
- Converts signal into time-frequency domain
- Produces a spectrogram

### 3. Spectrogram
- 2D representation (time vs frequency)
- Used as input for CNN

### 4. CNN Model
- Extracts patterns from spectrogram
- Predicts future stock values

---

## 🛠️ Technologies Used
- Python
- NumPy
- Matplotlib
- SciPy (STFT)
- TensorFlow / Keras
- Scikit-learn

---

## 📈 Results
- Model successfully trained on spectrogram data
- Training loss decreased over epochs
- Achieved Mean Squared Error (MSE): **0.169**

---

## 🧠 Key Insights
- Financial time series are non-stationary
- STFT reveals hidden time-frequency patterns
- CNN effectively learns from spectrogram images

---

## 🚀 How to Run
1. Open the notebook (.ipynb)
2. Run all cells sequentially
3. View plots and results

---

## 📌 Conclusion
This project demonstrates that combining signal processing with deep learning improves financial time series analysis and prediction accuracy.

---

## 👨‍💻 Author
Amrutha
