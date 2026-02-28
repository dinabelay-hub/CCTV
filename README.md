# Postpartum Infection Detection Using Machine Learning

This repository contains the implementation of a machine learning pipeline for **real-time detection of postpartum infections** using vital signs (Body Temperature and Heart Rate). The work is part of ongoing research for **ICIP** submissions.

---

## 📂 Repository Contents

- `logreg_pipeline.pkl` — Saved Logistic Regression pipeline (scaler + model)  
- `rf_pipeline.pkl` — Saved Random Forest pipeline (optional)  
- `notebooks/` — Jupyter/Colab notebooks with preprocessing, training, evaluation, and visualization  
- `README.md` — Project overview and instructions  

---

## 🧪 Dataset

The model uses a vital-signs dataset. Due to size restrictions, the dataset is hosted externally. You can download it here:

[Low-Light Image Dataset (LoL-Dataset) on Hugging Face](https://huggingface.co/datasets/geekyrakshit/LoL-Dataset)  

> Note: Only the relevant columns (Body Temp, Heart Rate) are used for model training.  

**Optional:** Include a small subset of the dataset in `sample_data/` for testing the pipeline quickly.

---

## ⚙️ Installation

Clone this repository and install required packages:

```bash
git clone https://github.com/dinabelay-hub/postpartum_infection_detection.git
cd postpartum_infection_detection
pip install -r requirements.txt
