# Bi-Level Prediction Model for Screening COVID-19 from Chest X-Ray Images

**Authors:** Soham Das, Soumya Deep Roy, Samir Malakar, Juan D. Velásquez, Ram Sarkar  
**Published in:** *Big Data Research* (Elsevier), April 2021  
**Paper Link:** [📄 Read the Full Paper on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2214579621000502)  
**DOI:** S2214-5796(21)00050-2

---

##  Abstract

We present a novel **bi-level classification model** for distinguishing between **Normal**, **Pneumonia**, and **COVID-19** patients using chest X-ray (CXR) images. Our approach consists of:

1. **Level-1:** Classify subjects as *Normal* or *Infected (Pneumonia + COVID-19)*.  
2. **Level-2:** For *Infected* cases, further differentiate between *Pneumonia* and *COVID-19*.

Deep features are extracted using **VGG19**, followed by **shallow learner classifiers** (Logistic Regression, k-NN, CART, Random Forest, XGBoost).  
The model is evaluated on a **balanced dataset of 3,168 CXR images** and achieves **99.26% accuracy**, outperforming single-level classification (96.74% accuracy).

---

##  Repository Structure

├── Feature Extraction_vgg19 (1).ipynb # Extracts VGG19 features for bi-level classification
├── Flow chart.jpg # Workflow diagram of the bi-level model
├── Test_hier.ipynb # Notebook for hierarchical (two-level) testing
├── Testing_covidxc.ipynb # Testing pipeline for COVID-positive classification
├── Testing_lv2_covidxc.ipynb # Second-level classification notebook (Pneumonia vs COVID)
└── README.md # This documentation file

<img width="528" height="857" alt="Screenshot 2025-08-17 at 3 33 32 AM" src="https://github.com/user-attachments/assets/7ab8332d-a86c-4cd4-bfe3-429507b1a36a" />
