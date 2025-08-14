# Bi-Level Prediction Model for Screening COVID-19 from Chest X-Ray Images

**Authors:** Soham Das, Soumya Deep Roy, Samir Malakar, Juan D. Velásquez, Ram Sarkar  
**Published in:** *Big Data Research* (Elsevier), April 2021  
**Paper Link:** [📄 Read the Full Paper on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2214579621000502)  
**DOI:** S2214-5796(21)00050-2

---

##  Abstract

The ongoing pandemic due to coronavirus disease, commonly abbreviated as COVID-19, has unleashed a major health crisis across the world. Although multiple vaccines have emerged, large scale vaccination have proven to be a major challenge, especially in developing nations. As a result, early detection still remains a crucial aspect of containing the spread of the virus. The popularly used test for COVID-19 is limited by the availability of test kits and is time-consuming. This has prompted researchers to use chest x-ray (CXR) and chest tomography (CT) scan images of subjects to predict COVID. Many COVID-19 patients also suffer from viral Pneumonia caused by SARS-CoV2 virus. Hence, distinguishing between bacterial and non-COVID Pneumonia is of paramount importance for proper diagnosis of the patients. To this end, in the present work, we have developed a bi-level prediction model of the subjects into normal, Pneumonia and COVID-19 patients by using a shallow learner based classifier on features extracted by VGG19 from the CXR images. The model is used on 3168 images distributed among normal, Pneumonia and COVID classes. We have created a dataset by collating CXR images from various sources like SIRM COVID-19 Database, Chest Imaging (Twitter), COVID-chestxray-dataset and Chest X-Ray Images. The experimental results confirm the superiority of the proposed model (99.26% accuracy) over the best performing single-level classification method (96.74% accuracy). This result is also at par with the many state-of-the-art methods mentioned in literature.
---

##  Repository Structure

├── Feature Extraction_vgg19 (1).ipynb # Extracts VGG19 features for bi-level classification
├── Flow chart.jpg # Workflow diagram of the bi-level model
├── Test_hier.ipynb # Notebook for hierarchical (two-level) testing
├── Testing_covidxc.ipynb # Testing pipeline for COVID-positive classification
├── Testing_lv2_covidxc.ipynb # Second-level classification notebook (Pneumonia vs COVID)
└── README.md # This documentation file
