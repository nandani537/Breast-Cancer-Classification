# 🏥 Breast Cancer Classification  
**Via SuperDataScience Team**  

Breast cancer is the most common cancer among women worldwide, accounting for **25% of all cancer cases** and affecting **2.1 million people** in 2015.  
Early diagnosis **significantly increases** the chances of survival.  

## **🩺 Problem Statement**  
The challenge in breast cancer detection is classifying tumors into **malignant** (cancerous) or **benign** (non-cancerous).  
Machine Learning techniques can **improve diagnosis accuracy** beyond traditional medical expertise.  

#### **👩‍⚕️ Traditional Diagnosis Accuracy:**  
👨‍⚕️ Experienced physicians: **79% accuracy**  
🤖 Machine Learning (SVM): **97% accuracy**  

---

## **📊 Dataset Information**  
Dataset: **Breast Cancer Wisconsin (Diagnostic)**  
**Source:** [UCI Machine Learning Repository](https://goo.gl/U2Uwz2)  

- **🧬 Features:** 30  
- **📦 Total Samples:** 569  
- **🩸 Class Distribution:**  
  - **Malignant:** 212  
  - **Benign:** 357  

#### **📌 Features Used in Classification**  
- **Radius**  
- **Texture**  
- **Perimeter**  
- **Area**  
- **Smoothness**  
- **Compactness**  
- **Concavity**  
- **Symmetry**  
- **Fractal Dimension**  

---

## **🔍 Machine Learning Approach**  
We use **Support Vector Machine (SVM)** for classification.  

- **🔹 Step 1:** Extract **features** from tumor images.  
- **🔹 Step 2:** Train the SVM model using labeled data.  
- **🔹 Step 3:** Classify new tumor images as **malignant** or **benign**.  

### **🔬 Model Training Steps**
1. Load **Breast Cancer Dataset** from Scikit-learn.
2. Visualize **correlations** and distributions.
3. **Train-Test Split** (80% train, 20% test).
4. Train **SVM classifier**.
5. Evaluate performance using **confusion matrix & accuracy**.
6. **Optimize** model using `GridSearchCV`.


### 🎯 Results & Conclusion
✅ SVM Classification Accuracy: 97%
✅ Early detection saves lives!
✅ Can be improved by deep learning & image classification.

### 🚀 Future Improvements
🔹 Implement CNN (Convolutional Neural Networks) for image-based detection.
🔹 Improve feature selection using Principal Component Analysis (PCA).
🔹 Deploy the model as a Web API for real-world applications.

### 📌 References
📜 Dataset: UCI Machine Learning Repository
📘 Scikit-Learn Documentation: https://scikit-learn.org
📖 Research Paper: Breast Cancer Diagnosis and Prognosis via Linear Programming
