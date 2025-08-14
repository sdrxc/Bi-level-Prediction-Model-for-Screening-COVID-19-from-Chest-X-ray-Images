# Bi-Level Prediction Model for Screening COVID-19 from Chest X-Ray Images

**Authors:** Soham Das, Soumya Deep Roy, Samir Malakar, Juan D. Velásquez, Ram Sarkar  
**Published in:** *Big Data Research* (Elsevier), April 2021  
**Paper Link:** [📄 Read the Full Paper on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2214579621000502)  
**DOI:** S2214-5796(21)00050-2

---

##  Abstract

We present a novel **bi-level classification model** for distinguishing between **normal**, **Pneumonia**, and **COVID-19** patients using chest X-ray (CXR) images. Our approach comprises two stages:

1. **Level-1:** Classify subjects as either *Normal* or *Infected (Pneumonia + COVID-19)*.  
2. **Level-2:** Among those predicted as infected, further distinguish between *Pneumonia* and *COVID-19*.

We extract deep features using **VGG19**, then use **shallow learner classifiers** (Logistic Regression, k-NN, CART, Random Forest, XGBoost) for classification. Our balanced dataset of **3,168 CXR images**—sourced from repositories like SIRM, COVID-chestxray-dataset, and others—achieved a remarkable **99.26% accuracy**, outperforming traditional single-level models (96.74% accuracy) :contentReference[oaicite:0]{index=0}.

---

##  Repository Structure

├── Feature Extraction_vgg19 (1).ipynb # Extracts VGG19 features for bi-level classification
├── Flow chart.jpg # Workflow diagram of the bi-level model
├── Test_hier.ipynb # Notebook for hierarchical (two-level) testing
├── Testing_covidxc.ipynb # Testing pipeline for COVID-positive classification
├── Testing_lv2_covidxc.ipynb # Second-level classification notebook (Pneumonia vs COVID)
└── README.md # This documentation file
