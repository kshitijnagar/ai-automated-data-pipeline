# 🚀 AI-Driven Automated Data Generation & Self-Healing Pipeline

## 📌 Project Overview
In real-world business scenarios, data is rarely clean. This Capstone Project demonstrates an end-to-end data pipeline that programmatically generates synthetic enterprise data, injects realistic anomalies, and then utilizes Generative AI (LLMs) and Python logic to automatically detect and repair those errors without manual intervention.

## 🛠️ Key Features
- **Synthetic Data Generation:** Scalable mock data created using Python.
- **Anomaly Injection (Mutation):** Programmatic introduction of missing values, schema drifts, and formatting errors to test pipeline resilience.
- **AI-Powered Self-Healing:** Automated detection and correction of injected errors using LLMs.
- **Data Analytics:** Extraction of business insights and aggregation runs on the polished dataset.

## 📂 Project Structure
- `raw_generated_data.csv`: The initial synthetic dataset deliberately injected with noise and errors.
- `cleaned_final_data.csv`: The final dataset after the AI/Python self-healing logic has been applied.
- `*.ipynb` (Google Colab Notebook): The complete source code encompassing data generation, mutation, healing, and insight extraction.

## ⚙️ Technologies Used
- Python (Pandas, NumPy)
- Generative AI API (for self-healing logic)
- Google Colab

## 💡 The Takeaway
This project bridges the gap between theoretical data management and practical data execution. By handling unpredictable data mutations automatically, it showcases the crucial skill of building reliable and robust automated data quality pipelines for production environments.
