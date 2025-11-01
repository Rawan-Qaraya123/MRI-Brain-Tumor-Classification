# 🧠 MRI-Based Brain Tumor Classification Using Deep Learning Models

This repository presents the research paper titled **“MRI-Based Brain Tumor Classification Using Deep Learning Models”**, authored by **Rawan Aboalqaraya**, **Dr. Fatih Özyurt**, **Dr. Canan Koç**, and **Esra Yüzgeç**, and presented at the **3rd International Conference on Advances and Innovations in Engineering (ICAIE 2025)**.

🔗 **Conference Proceedings:** [ICAIE 2025 Book of Proceedings](https://icaie.firat.edu.tr/index.php/kongre/kongrekitabi)

---

## 📘 Abstract

This study focuses on the automatic classification of brain tumors from MRI images using deep learning techniques. The goal is to develop a reliable system that can distinguish between **glioma**, **meningioma**, **pituitary tumor**, and **no tumor** cases.  
Five deep learning models were evaluated — a custom **Convolutional Neural Network (CNN)**, **VGG16**, **VGG19**, **MobileNetV2**, and **ResNet50** — using transfer learning and data augmentation techniques.

---

## ⚙️ Methodology

- **Dataset:** Combined datasets from *Figshare*, *SARTAJ*, and *Br35H (Kaggle)*  
- **Preprocessing:** Image resizing (240×240), normalization, and augmentation (rotation, flipping, zoom)  
- **Models Used:**
  - Custom CNN  
  - VGG16  
  - VGG19  
  - MobileNetV2  
  - ResNet50  
- **Optimizer:** Adam  
- **Loss Function:** Categorical Cross-Entropy  
- **Training Epochs:** 20  
- **Callbacks:** EarlyStopping, ReduceLROnPlateau  

---

## 📊 Results

| Model | Test Accuracy |
|--------|----------------|
| Custom CNN | **90.08%** |
| MobileNetV2 | 89.09% |
| VGG16 | 80.70% |
| VGG19 | 79.32% |
| ResNet50 | 67.42% |

The **custom CNN model** achieved the best overall performance, demonstrating that task-specific architectures can outperform larger pre-trained models when optimized effectively.

---

## 🧪 Evaluation Metrics

- Accuracy  
- Precision  
- Recall (Sensitivity)  
- F1-Score  
- Confusion Matrix  

---

## 🧩 Conclusion

The proposed deep learning approach successfully classifies MRI brain images with high accuracy.  
The results prove that deep learning-based methods can significantly support medical professionals by automating the tumor detection and classification process.

---

## 🏫 Authors & Affiliation

- **Rawan Aboalqaraya** — Department of Software Engineering, Fırat University  
- **Dr. Fatih Özyurt** — Department of Software Engineering, Fırat University  
- **Dr. Canan Koç** — Department of Software Engineering, Fırat University  
- **Esra Yüzgeç** — Department of Software Engineering, Fırat University  

---

## 🏅 Publication Details

📘 **Presented at:** 3rd International Conference on Advances and Innovations in Engineering (ICAIE 2025)  
📅 **Date:** October 2025  
🔗 **Conference Book:** [ICAIE 2025 Proceedings](https://icaie.firat.edu.tr/index.php/kongre/kongrekitabi)

---

## 🖼️ Certificate

<p align="center">
  <img src="3ICAIE2025_PresentationCertificate_Rawan%20ABOALQARAYA_page-0001.jpg" alt="Conference Certificate" width="600">
</p>
