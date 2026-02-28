# Low-Light CCTV Image Enhancement

This repository contains code for enhancing **low-light CCTV images** using classical image processing techniques such as **CLAHE**, **Gamma Correction**, and **Denoising**. It also includes quantitative evaluation using **PSNR**, **SSIM**, and **BRISQUE** metrics.  

This project is part of research work for **ICIP**.

---

## 📂 Repository Contents

- `notebooks/` — Colab/Jupyter notebooks with preprocessing, enhancement, and evaluation pipelines  
- `figures/` — Example images generated during experiments  
- `README.md` — This file  

> ⚠️ The full dataset is **too large** to host here.  

---

## 🧪 Dataset

We used the **LoL-Dataset (Low-Light Images)**:

[LoL-Dataset on Hugging Face](https://huggingface.co/datasets/geekyrakshit/LoL-Dataset)

- Contains **low-light input images** and **ground truth images**  
- Use the `train` or `test` splits depending on your experiments  
- Download and unzip; update paths in the notebook accordingly  

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/dinabelay-hub/lowlight-cctv-enhancement.git
cd lowlight-cctv-enhancement
pip install -r requirements.txt
