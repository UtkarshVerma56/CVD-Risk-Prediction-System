# CVD Risk Prediction System

## About the Project
This project focuses on predicting the 10-year risk of cardiovascular disease (CVD) using machine learning techniques on clinical patient data. The goal of the system is to provide accurate, reliable, and explainable risk predictions that can support early healthcare decision-making.

The model was trained on around 15,000 clinical records using LightGBM and further improved using isotonic calibration for better probability estimation. In addition to model performance, the project also emphasizes fairness by analyzing prediction bias across different demographic groups such as age, gender, and race.

An interactive Streamlit dashboard was developed to make the system easy to use and accessible through the cloud.

---

## Key Features
- Predicts long-term cardiovascular disease risk using patient clinical data
- Built with LightGBM for efficient and accurate classification
- Uses isotonic calibration for reliable probability predictions
- Performs fairness analysis using FairLearn
- Includes SHAP explainability for transparent predictions
- Interactive Streamlit dashboard for real-time predictions
- Fast inference latency below 50ms
- Cloud-accessible deployment with no local setup required

---

## Tech Stack
- Python
- LightGBM
- Scikit-learn
- FairLearn
- SHAP
- Streamlit
- Pandas
- NumPy

---

## Model Performance

| Metric | Score |
|--------|--------|
| AUC Score | 0.87 |
| Brier Score | 0.12 |
| Inference Time | <50ms |
| Demographic Parity Gap | ≤0.08 |

---

## Fairness and Explainability
The project includes fairness auditing to evaluate how the model performs across different demographic groups. Threshold optimization techniques were applied to reduce screening bias and improve fairness in predictions.

SHAP explainability was integrated to help users understand the contribution of different clinical features behind each prediction, making the model more transparent and interpretable.

---


---

## Future Improvements
- Add deep learning-based prediction models
- Deploy using Docker and Kubernetes
- Integrate real-time healthcare data pipelines
- Improve fairness mitigation techniques

---

