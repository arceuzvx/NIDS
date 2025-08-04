# 🛡️ Network Intrusion Detection System (NIDS) — AI Inference MVP

This project is a prototype AI-based **Network Intrusion Detection System (NIDS)** that performs **inference only** on pre-processed network traffic data. It utilizes a pre-trained machine learning model to classify network activity as normal or malicious.

## 🎯 Project Goal

To deploy a lightweight, inference-ready AI agent capable of detecting potential network intrusions in real time, with potential future integration into IBM Cloud environments.

---

## 🧠 Features

- Inference-ready, no training pipeline.
- Compatible with IBM Cloud environments (Watson Studio, Cloud Notebooks).
- Model can classify data into various attack categories (based on NSL-KDD or similar datasets).
- Simplified UI via Jupyter Notebook for proof-of-concept testing.

---

## 🧰 Technologies Used

- **Python 3.x**
- **scikit-learn**
- **pandas, numpy**
- **Jupyter Notebook**
- **IBM Cloud Lite Account (optional)**
  - [Watson Studio](https://dataplatform.cloud.ibm.com/)
  - [Cloud Object Storage](https://www.ibm.com/cloud/object-storage)

---

## 🚀 How to Run (Locally or in IBM Watson Studio)

### Option 1: Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/NIDS-Inference-MVP.git
   cd NIDS-Inference-MVP
   
2. Create a virtual environment and install dependencies

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    pip install -r requirements.txt


3. Open the notebook
   ```bash
    jupyter notebook
4. Run ```Network Intrusion Detection System copy.ipynb``` for predictions.

