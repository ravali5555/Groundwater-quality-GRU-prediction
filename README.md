# 🌊 Groundwater Quality Forecasting using GRU Neural Network

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview

Groundwater is one of the most important natural resources for drinking, agriculture, and industrial use. Monitoring and forecasting groundwater quality helps authorities make informed decisions for sustainable water management.

This project develops a **Gated Recurrent Unit (GRU)** based Deep Learning model to forecast groundwater quality using historical water quality measurements. The performance of the GRU model is also compared with several baseline machine learning algorithms.

---

## 🎯 Objectives

- Predict groundwater quality using historical data.
- Develop a GRU-based deep learning forecasting model.
- Compare GRU with baseline machine learning models.
- Visualize model performance using training graphs.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
Groundwater-quality-GRU-prediction
│
├── data
│   └── water_quality_dataset.csv
│
├── notebooks
│   ├── GRU_Model.ipynb
│   └── Baseline_Models.ipynb
│
├── images
│   ├── Accuracy.png
│   └── Loss.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧠 Deep Learning Model

The project uses a **Gated Recurrent Unit (GRU)** neural network to learn temporal patterns from groundwater quality data.

### Workflow

```
Dataset
     ↓
Data Preprocessing
     ↓
Feature Scaling
     ↓
GRU Neural Network
     ↓
Model Training
     ↓
Prediction
     ↓
Performance Evaluation
```

---

## 📊 Model Performance

### Training Accuracy

![Accuracy](images/Accuracy.png)

---

### Training Loss

![Loss](images/Loss.png)

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/ravali5555/Groundwater-quality-GRU-prediction.git
```

Install dependencies

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn
```

Run

- Open `GRU_Model.ipynb`
- Execute all notebook cells

---

## 📈 Results

The GRU model successfully learns temporal groundwater quality patterns and provides accurate forecasting.

The repository also includes baseline machine learning models for comparison.

---

## 🔮 Future Work

- Hyperparameter optimization
- LSTM and Bi-LSTM comparison
- Real-time groundwater monitoring
- Web application deployment
- Explainable AI (XAI)

---

## 👩‍💻 Author

**Pilli Ravali**

Research Project:
**Groundwater Quality Forecasting using GRU Neural Network**

---

## 📜 License

This project is licensed under the MIT License.

