# Bangla Speech Emotion Recognition (SER)

This repository contains visual results supporting a research study on **Bangla Speech Emotion Recognition (SER)** using traditional machine learning models. The experiments are conducted on two benchmark Bangla emotional speech datasets: **SUBESCO** and **KBES**.

The primary objective of this repository is to present **performance visualizations**, **comparative analyses**, and **dimensionality reduction effects** used in the study.

---

## Abstract

Speech Emotion Recognition (SER) plays a vital role in Human–Computer Interaction (HCI); however, robust SER systems for the Bangla language remain largely underexplored. This work proposes a novel framework that enhances Bangla SER performance through extensive feature fusion and a multifaceted dimensionality reduction strategy.

We fuse diverse acoustic features from the time domain, frequency domain, and time–frequency domain—including Amplitude Envelope, Zero-Crossing Rate, Mel-Frequency Cepstral Coefficients (MFCCs), and Spectral Centroid—by computing statistical descriptors. To construct a compact yet discriminative feature representation, we apply Principal Component Analysis (PCA), Independent Component Analysis (ICA), and Linear Discriminant Analysis (LDA).

The proposed approach is evaluated on two Bangla emotional speech datasets: SUBESCO (7 emotions) and KBES (9 emotions), using four machine learning classifiers—k-Nearest Neighbors (k-NN), Decision Tree, Random Forest, and XGBoost. Experimental results show that the Random Forest classifier combined with the proposed feature-reduction pipeline achieves the best performance, with 97.78% accuracy on KBES and 87.14% accuracy on SUBESCO, while utilizing only a fraction of the original feature set.

These results demonstrate that the proposed strategy significantly improves emotion recognition accuracy while substantially reducing feature dimensionality, leading to more efficient SER systems for under-resourced languages such as Bangla.

---

## 🔍 Key Contributions

- Feature fusion with summary statistics  
- Dimensionality reduction using **PCA**, **ICA**, and **LDA**  
- Multifaceted learning framework  
- Comparative analysis of classical ML classifiers  

---

## 📁 Datasets

- **SUBESCO** – SUST Bangla Emotional Speech Corpus  
- **KBES** – Khulna Bangla Emotional Speech Dataset  

---

## 🔬 Methodology Overview

The complete pipeline illustrating feature extraction, fusion, dimensionality reduction, and classification:

<img width="1283" height="708" src="https://github.com/user-attachments/assets/ae4ade26-1885-4d4f-b8df-3f7a8c83a8d5" />

---

## 🧩 Multifaceted Dataset Architecture

The multifaceted architecture representing dataset handling and learning stages:

<img width="1000" height="536" src="https://github.com/user-attachments/assets/69d5e1a8-f2d3-4a25-845f-3b41b708c9ff" />

---

## 📊 Model Performance Results

Performance analysis of different classifiers on both datasets.

---

### 🌳 Decision Tree

**KBES Dataset**  
<img src="https://github.com/user-attachments/assets/c0d8779a-1bf5-43b8-ba6d-3013a67e2209" width="500"/>

**SUBESCO Dataset**  
<img src="https://github.com/user-attachments/assets/6a99a02c-5d28-4531-9833-14db385f084a" width="500"/>

---

### 🔍 K-Nearest Neighbors (KNN)

**KBES Dataset**  
<img src="https://github.com/user-attachments/assets/126b3083-294a-4305-a253-71b90d9141ad" width="500"/>

**SUBESCO Dataset**  
<img src="https://github.com/user-attachments/assets/8e8a44d8-a1f1-4a03-85a9-42d9ceeaef70" width="500"/>

---

### 🌲 Random Forest (RF)

**KBES Dataset**  
<img src="https://github.com/user-attachments/assets/fedb1521-8c4b-4e94-8d24-ae6983327201" width="500"/>

**SUBESCO Dataset**  
<img src="https://github.com/user-attachments/assets/b62e8015-5c0a-4ff5-9cd8-6b7b17f1a308" width="500"/>

---

### 🚀 XGBoost

**KBES Dataset**  
<img src="https://github.com/user-attachments/assets/ce44e7d1-2056-4091-93b2-539a9fd09cd9" width="500"/>

**SUBESCO Dataset**  
<img src="https://github.com/user-attachments/assets/66aab63c-4a64-47fb-8a06-45da13786e46" width="500"/>

---

## 🔍 Additional Analysis

### 📉 Confusion Matrix (Random Forest)

**SUBESCO Dataset**  
<img src="https://github.com/user-attachments/assets/4be82d25-23ac-40b1-9862-70cf01ea9c37" width="500"/>

**KBES Dataset**  
<img src="https://github.com/user-attachments/assets/57bbf324-53c0-43fc-8020-e2f5da3fb96b" width="500"/>

---

### 📈 Accuracy Analysis – SUBESCO Dataset

**Without Dimensionality Reduction**  
<img src="https://github.com/user-attachments/assets/db759a7f-cab2-4578-a47c-0bccbbc27b68" width="500"/>

**With Dimensionality Reduction (PCA / ICA / LDA)**  
<img src="https://github.com/user-attachments/assets/de9135b1-067f-4757-b1ef-56516f450e54" width="500"/>

---

### 📈 Accuracy Analysis – KBES Dataset

**Without Dimensionality Reduction**  
<img src="https://github.com/user-attachments/assets/c5f1f04c-3f31-4f60-8a4b-2b110c13628b" width="500"/>

**With Dimensionality Reduction (PCA / ICA / LDA)**  
<img src="https://github.com/user-attachments/assets/abc74692-a164-468d-b9b8-8cefefd7a1f0" width="500"/>

---

## 🧠 Models Used

- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Random Forest  
- XGBoost  

---

## 📌 Notes

- This repository focuses on **visual and experimental results only**
- The code implementation is part of the associated research work
- Figures are intended for **journal/conference publication support**

---
## 📬 Contact

**Author:** Abu Omayed  
📧 **Email:** abuomayed@gmail.com  

---
## 📜 License

This project is for **academic and research purposes only**.



