# EEG-Based Multiclass Thought Recognition Using Hybrid Deep Learning

## 📊 Dataset Description

We use the publicly available **Kumar's EEG Imagined Speech Dataset**, which contains EEG signals collected from three subjects imagining:

- **Digits (0–9)**
- **English characters (A–J)**
- **Objects (common image categories)**

📥 Dataset source:  
[https://www.kaggle.com/datasets/ignazio/kumars-eeg-imagined-speech](https://www.kaggle.com/datasets/ignazio/kumars-eeg-imagined-speech)

---

## ⚠️ Disclaimer

This work is **independently developed** for academic purposes. It is **inspired by** the approach in the paper:

> P. Kumar, R. Saini, P. P. Roy, P. K. Sahu, D. P. Dogra,  
> *Envisioned Speech Recognition Using EEG Sensors*,  
> *Personal and Ubiquitous Computing*, 22(1): 185–199, 2018.


---

## 🧠 Model Architecture

The proposed architecture combines **Convolutional Neural Networks (CNN)** with **Multi-Head Attention** to extract both spatial and contextual temporal features from raw EEG signals.

![Model Architecture](https://github.com/user-attachments/assets/9916036a-b6b4-45ef-8b9f-867df0eb3e09)

---

## 🛠️ Tools & Technologies

- Python
- TensorFlow & PyTorch
- MNE (EEG signal processing)
- NumPy, SciPy, Matplotlib, Seaborn

---

## 🎯 Outcomes

- **Digits classification**: 92.07% accuracy  
- **Characters classification**: 91.78% accuracy  
- **Objects classification**: 93.60% accuracy

---

## 📂 Repository Structure


