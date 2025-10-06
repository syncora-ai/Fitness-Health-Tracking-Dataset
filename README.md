# Wearable Activity Dataset ⌚ — Fitness & Health Tracking Data

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

A **free wearable activity dataset** with steps, heart rate, calories, and distance metrics from fitness trackers. Privacy-safe synthetic data for ML pipelines, activity recognition, health analytics, time-series forecasting, and feature engineering. Also usable as a **dataset for LLM training**.

---

## 🏋️ Dataset Overview

This dataset contains **wearable fitness and biometric data**, modeled on devices like the Apple Watch. All entries are **synthetic**, privacy-safe, and ready for **ML pipelines**. Suitable for predictive modeling, activity classification, and **LLM-based experiments**.

| Column | Description |
|--------|-------------|
| `age` | Age of the user (years) |
| `gender` | Gender encoded as 0 = female, 1 = male |
| `height` | Height in cm |
| `weight` | Weight in kg |
| `steps` | Daily step count |
| `heart_rate` | Active heart rate |
| `resting_heart` | Resting heart rate |
| `calories` | Estimated calorie burn |
| `distance` | Distance traveled (km) |
| `entropy_heart` | Entropy of heart rate signals |
| `entropy_steps` | Entropy of steps |
| `corr_heart_steps` | Correlation between heart rate & steps |
| `intensity_karvonen` | Exercise intensity via Karvonen formula |
| `device` | Wearable source (Apple Watch) |
| `activity` | Activity label (e.g., Lying, Walking) |

---

## 📦 What's Inside

- **Dataset CSV** – Contains all wearable metrics and activity labels  
  [⬇️ Download Dataset](https://github.com/syncora-ai/Wearable-Activity-Dataset/blob/main/wearables_monitoring_data.csv)  

- **Jupyter Notebook** – Explore and analyze dataset  
  [📓 Open Notebook](https://github.com/syncora-ai/Fitness-Health-Tracking-Dataset/blob/main/apple_watch_fitbit_data_synthetic%20(1).ipynb)  

---

## 📊 Use Cases

- **Activity Recognition**: Train ML models to classify physical states (Lying, Walking, Running)  
- **Time-Series Forecasting**: Predict steps, calories, or heart rate over time  
- **Health & Wellness Analytics**: Analyze biometric signals for fitness insights  
- **LLM Training**: Convert structured wearable data into text prompts — perfect as a **dataset for LLM training**  
- **Feature Engineering & Explainability**: Use SHAP, LIME, or ELI5 for interpreting biometric model predictions  
- **Benchmarking & Model Validation**: Test predictive performance on realistic wearable datasets  

---

## 🔗 Resources

- **⚡ Synthetic Data Generator** – Build your own datasets  
  [Open Generator](https://huggingface.co/spaces/syncora/synthetic-generation)  

- **🌐 Syncora.ai** – Learn more about the platform powering this dataset  
  [Visit Website](https://syncora.ai)  

---

## 📜 License

Released under **Apache License 2.0**.  

This is a **100% free dataset**, ready for ML research, activity recognition, health analytics, and **dataset for LLM training**.
