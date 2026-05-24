# 🧠 ALZHEIMER’S DISEASE DETECTION FROM MRI IMAGE USING DEEP 
LEARNING APPROACH

## 📌 Project Overview
This project focuses on the early detection of **Alzheimer’s Disease (AD)** using **MRI brain images** and **Deep Learning (CNN)**. The goal is to develop an automated system that can accurately classify different stages of Alzheimer’s disease.

Early detection is very important because timely treatment can slow down disease progression and improve patient outcomes.

---

## 🎯 Objectives
- Develop a **CNN-based model** for Alzheimer’s detection
- Classify MRI images into different stages:
  - Non-Demented
  - Very Mild Demented
  - Mild Demented
  - Moderate Demented
- Improve diagnostic accuracy using deep learning
- Assist healthcare professionals with automated diagnosis

---

## 🧪 Methodology

### 🔹 Data Collection
- Dataset collected from:
  - Kaggle MRI dataset
  - Public datasets (ADNI, OASIS)
- ~5000 training images and ~1200 testing images

### 🔹 Data Preprocessing
- Image normalization
- Resizing (e.g., 224x224)
- Data augmentation:
  - Rotation
  - Flipping
  - Scaling

### 🔹 Model Architecture
- Convolutional Neural Network (CNN)
- Layers include:
  - Convolutional layers
  - Pooling layers
  - Fully connected layers
  - Softmax output layer

### 🔹 Training Process
- Train/Validation/Test split (80/10/10)
- Loss function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - AUC-ROC

---

## 📊 Results
- Achieved approximately **80% accuracy**
- Successfully classified MRI images into four categories
- Model shows strong potential for early-stage detection

---

## 🛠️ Technologies Used

- **Programming Language:** Python 3.9  
- **Libraries & Frameworks:**
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib  
- **Tools:**
  - Anaconda Navigator
  - Jupyter Notebook / Spyder  
- **Platform:** Windows 10  

---

## 🔄 Workflow

1. Collect MRI images  
2. Preprocess data  
3. Train CNN model  
4. Validate and test model  
5. Evaluate performance  
6. Predict Alzheimer’s stage  

---

## 📈 Features
- Automated MRI image classification  
- Multi-class disease stage detection  
- Deep learning-based approach  
- Scalable and reproducible system  

---

## 🚧 Limitations
- Limited dataset size  
- Requires high computational resources  
- Model generalization needs improvement  

---

## 🔮 Future Work
- Use larger and more diverse datasets  
- Apply advanced models (e.g., Transformers)  
- Combine MRI with other data (PET scans, clinical data)  
- Improve model interpretability (Grad-CAM)

---

## 👨‍🎓 Author
**Md. Abu Rayhan**  
B.Sc. in Computer Science and Engineering  
Hamdard University Bangladesh  

---

## 👨‍🏫 Supervisor
**Md. Afzalur Rahaman**  
Lecturer, Department of CSE  
Hamdard University Bangladesh  

---

## 📜 License
This project is for academic and research purposes only.

---

## ⭐ Acknowledgement
Special thanks to my supervisor, faculty members, and family for their support in completing this project.

---
