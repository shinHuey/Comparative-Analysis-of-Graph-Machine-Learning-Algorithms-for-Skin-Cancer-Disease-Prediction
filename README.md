# 🧬 Skin Cancer Prediction Using Graph Neural Networks

This repository implements a **graph-based machine learning approach** to predict skin cancer from images, using PyTorch Geometric.

---

## 📌 Project Overview
- Utilises the **HAM10000** skin lesion dataset from Kaggle  
- Transforms dermoscopic image segments into graph structures  
- Trains **Graph Neural Networks** (e.g., GCN) for lesion classification  

---

## 📂 Dataset

| Dataset | Description |
|--------|-------------|
| **HAM10000 (Kaggle)** | Diverse collection of 10,015 dermatoscopic images of pigmented skin lesions spanning 7 diagnostic categories. [(Download here)](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) |

**Usage:**  
Place the extracted dataset in a suitable folder (e.g., `data/HAM10000/`) in your Google Drive before running the notebook.

---

## 🧰 Libraries Used
- **Deep Learning:** PyTorch & PyTorch Geometric  
- **Data Handling:** Pandas, NumPy  
- **Imaging:** Matplotlib, OpenCV, PIL  
- **Preprocessing & ML:** Scikit-learn  

---

## 📁 Workflow Outline
1. Mount Google Drive and setup working directory  
2. Install dependencies and import libraries  
3. Load and preprocess image data & metadata  
4. Segment images and convert into graph objects  
5. Split data into training, validation, and test sets  
6. Define & train a Graph Convolutional Network (GCN)  
7. Evaluate performance using accuracy, loss curves, and test metrics  

---

## 🚀 How to Run
Designed for **Google Colab** execution:
1. Upload `Skin_Cancer.ipynb` to Colab  
2. Ensure Kaggle credentials are set (to download HAM10000 automatically)  
3. Run all cells sequentially to train and evaluate the model

---

## 📊 Results
- Training and validation loss/accuracy plotted live  
- Model achieves ~95% accuracy on the test dataset  
- Confusion matrix and classification report included  

---

## 👩‍💻 Author
**Shin Huey Lim**  
MSc in Big Data & Data Science Technology, Northumbria University London  
[LinkedIn](https://www.linkedin.com/in/shinhuey-lim-datascientist/)
