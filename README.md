# ❤️ ECG Heartbeat Classification (Machine Learning & Deep Learning)

An end-to-end project that classifies ECG signals into normal and abnormal heartbeats using both **Machine Learning** and **Deep Learning** algorithms.

---

## 🧠 Project Overview
This project demonstrates how machine learning and deep learning can be used to detect cardiac abnormalities from ECG signals. It compares multiple models to evaluate accuracy, recall, and F1-score, aiming to assist in early detection of arrhythmia.

---

## ⚙️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🧾 Dataset
- Source: [MIT-BIH Arrhythmia Database](https://www.physionet.org/content/mitdb/1.0.0/)
- Features: Heartbeat signal data (time series)
- Target: Heartbeat class (Normal, PVC, LBBB, RBBB, etc.)

---

## 🧩 Methodology
1. Data Cleaning & Normalization  
2. Signal Segmentation & Feature Extraction  
3. Model Building:
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Random Forest  
   - Convolutional Neural Network (CNN)  
   - Long Short-Term Memory (LSTM)  
4. Model Evaluation using Accuracy, F1-score, ROC-AUC  
5. Comparison between ML & DL models  

---

## 📈 Results
| Model | Accuracy | F1-Score | ROC-AUC |
|--------|-----------|----------|----------|
| Random Forest | 90% | 0.88 | 0.91 |
| CNN | 95% | 0.93 | 0.96 |
| LSTM | 97% | 0.95 | 0.98 |

✅ **Best Model:** LSTM (Deep Learning)  

---

## 📂 Files Included
| File | Description |
|------|--------------|
| `ecg_heartbeat_classification.ipynb` | Full code with EDA, ML, and DL models |
| `ecg_heartbeat_data.csv` | Dataset used for model training |
| `ECG_Classification_Report.docx` | Detailed project report |
| `ECG_Insights.pdf` | Summary report with charts and visual insights |

📘 *All results and visual outputs are available in the report files.*

---

## 🚀 Future Enhancements
- Integrate real-time ECG signal input  
- Develop a web-based dashboard using Streamlit or Flask  
- Deploy model for live arrhythmia detection  

---

## 👨‍💻 Author
**Hemant Kumar M**  
📍 Newcastle upon Tyne, UK  
📧 hihemantkumar786@gmail.com  
🔗 GitHub: [github.com/Hemant-Kumar786](https://github.com/Hemant-Kumar786)
