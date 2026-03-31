# 🎗️ Cancer Risk Intelligence & Predictive Analytics Platform

An end-to-end clinical decision support tool designed to analyze behavioral, environmental, and clinical risk factors for lung cancer. This project leverages **Ensemble Machine Learning** and **Interactive Data Visualization** to provide real-time risk assessments and actionable medical recommendations.

---

## 🚀 Project Overview

This platform was developed to bridge the gap between static epidemiological data and clinical utility. By analyzing a dataset of 1,000 patients across 25 high-dimensional features, the system identifies non-linear risk patterns and provides an interactive interface for researchers and healthcare providers to explore patient demographics and risk drivers.

### ✨ Key Features

- **🔮 Predictive Engine**: Powered by a **Random Forest Classifier**, achieving 99%+ accuracy in categorizing patients into **Low**, **Medium**, and **High** risk levels based on multivariate feature interactions.
- **📊 Interactive EDA Engine**: A dynamic visualization suite allowing users to toggle between **Scatter Plots, Box Plots, Violin Plots, and Bar Charts** to explore feature distributions (e.g., Age vs. Air Pollution).
- **💡 Clinical Decision Support**: Beyond just predictions, the system serves **AI-generated medical recommendations**—from routine check-ups to urgent oncology referrals—tailored to the specific risk profile.
- **⚡ Performance-First Architecture**: Utilizes **Streamlit resource caching** to optimize model inference latency and ensure a seamless user experience even with complex data processing.
- **🩺 Holistic Risk Profile**: Analyzes a wide spectrum of factors, including **Genetic Risk, Obesity, Alcohol Use, Occupational Hazards, and Smoking habits.**

---

## 🛠️ Technology Stack

- **Framework**: [Streamlit](https://streamlit.io/) (Application & UI Logic)
- **Machine Learning**: [Scikit-learn](https://scikit-learn.org/) (Random Forest, Label Encoding, Data Splitting)
- **Data Engineering**: [Pandas](https://pandas.pydata.org/) (Feature Engineering & Binning)
- **Visual Analytics**: [Seaborn](https://seaborn.pydata.org/) & [Matplotlib](https://matplotlib.org/) (Multivariate Plotting)

---

## 📂 Project Architecture

```bash
├── dashboard.py                       # Main application & predictive logic
├── cancer patient data sets - Sheet.csv # Primary clinical dataset (1,000 records)
├── cancer_dataset_analysis.ipynb      # Initial R&D, EDA, and model testing
├── requirements.txt                   # Dependency manifests for deployment
└── README.md                          # Comprehensive project documentation
```

---

## ⚙️ Installation & Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Cancer-Risk-Analytics.git
   cd Cancer-Risk-Analytics
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Dashboard**:
   ```bash
   streamlit run dashboard.py
   ```

---
## 🚀 Try The App
 👉[Cancer Risk Prediction Dashboard](https://dashboardpy-7cbmjdc6gzg5rjdhjl9ihj.streamlit.app/)👈
---

## 🔬 Scientific Methodology

1. **Preprocessing**: Implemented automated data validation and cleaning pipelines. Categorical clinical markers (Age, Obesity) were discretized via **binning** to improve model interpretability.
2. **Modeling**: Evaluated multiple ensemble methods, selecting **Random Forest** for its robustness against high-dimensional noise and its ability to capture complex feature synergies (e.g., the interplay between Occupational Hazards and Genetic Risk).
3. **UX/UI**: Designed a stateful dashboard that allows for **"What-If" analysis**—users can adjust lifestyle parameters to see real-time changes in predicted risk level.

---

## ⚠️ Medical Disclaimer
This tool is for **demonstration and research purposes only.** The predictions are based on historical data patterns and should **not** be used as a substitute for professional clinical diagnosis. Always consult a licensed medical professional for health concerns.

---
*Developed for the intersection of Data Science and Preventive Oncology.*
