# ML Learning: Earthquake & Tsunami Detection

<!-- Badges -->
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)

## 🌍 Project Overview
This project focuses on detecting and classifying **earthquake and tsunami events** using **machine learning and deep learning techniques** on tabular geophysical data.  
It demonstrates an end-to-end ML workflow from data preprocessing, exploratory analysis, and model training, to evaluation and visualization.

The goal is to extract meaningful patterns from seismic data and provide insights that could support **early warning systems**.

---

## 🎯 Objectives
- Apply ML/DL models to classify earthquake and tsunami events.  
- Perform data preprocessing and exploratory data analysis (EDA).  
- Train, evaluate, and optimize models for accurate prediction.  
- Visualize patterns and correlations in seismic and tsunami data.  
- Provide a clean, reproducible project structure for future improvements.

---

## 📂 Folder Structure

ml-learning-earthquake-tsunami-detection/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for EDA, visualization, experimentation
├── code/ # Python scripts for preprocessing, training, evaluation
├── Visuals
└── README.md # Project documentation


---

## 🧰 Tools & Libraries
- Python 3.x  
- numpy, pandas, matplotlib, seaborn  
- scikit-learn  
- TensorFlow / Keras  
- joblib  

```bash
pip install -r requirements.txt
📈 Model & Results

Model Used: Simple Feedforward Neural Network

Architecture: 2 hidden layers (64, 32 neurons) with ReLU activation

Output: Sigmoid for binary classification

Confusion Matrix:

Predicted
         0     1
Actual 0  120   10
       1   8   105

⚠️ Limitations & Failures

The dataset is limited in size; results may vary on real-world larger datasets.

Model performance drops when feature distribution differs from training data.

Occasional false positives/negatives may occur in rare cases, affecting reliability.

Model currently works on offline data; real-time prediction is not implemented.

Only binary classification is implemented; multi-class detection of seismic events is future work.

🚀 Future Enhancements

Implement real-time earthquake/tsunami detection using streaming data.

Test advanced deep learning architectures (e.g., LSTM, CNN on seismic time series).

Build interactive dashboards for visualization and monitoring.

Extend to multi-class classification for different types of natural events.

✍️ Author

ABDULLAH
