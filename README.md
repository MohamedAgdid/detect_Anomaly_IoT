# 📊 DS2O Traffic Traces - Anomaly Detection Project

## Dataset

This project uses an **external dataset** for anomaly detection experiments on IoT/traffic traces.  

**Steps to reproduce:**

1. Download the dataset from Kaggle: [DS2O Traffic Traces](https://www.kaggle.com/datasets/francoisxa/ds2ostraffictraces)
2. Place the CSV file in the project folder of this repository.
3. Preprocess the data according to your pipeline (scaling, train/val/test split, etc.).
4. Run the scripts for the model(s) you want to test (Isolation Forest, Autoencoder, LSTM, XGBoost, etc.).

---

💡 **Note:**  
- Normal traffic is labeled `0`, anomalies labeled `1`.  
- Make sure to adjust thresholds if you experiment with unsupervised models (Isolation Forest, Autoencoder, LSTM).  

---

## 🛠 Installation

```bash
# create a virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows


pip install -r requirements.txt


---

Feel free to fork, experiment, and improve the anomaly detection pipeline 🚀
