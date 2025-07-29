# 👁️ Diabetic Retinopathy Detection from Retinal Images 🧬

## 📌 **Project Overview**
Welcome to the **Diabetic Retinopathy Classification** project! This deep learning model analyzes retinal fundus images to detect the presence and severity of diabetic retinopathy. It aids ophthalmologists by providing quick, reliable grading of retinal damage.

## 📂 **Dataset Information**

📄 **Dataset Source:** Fundus image dataset with labeled severity levels  
🧷 **Classes:**
- 0: No DR
- 1: Mild
- 2: Moderate
- 3: Severe
- 4: Proliferative DR

## 🖼️ **Image Features**

Each image reveals signs of retinal health or disease progression through:
- Microaneurysms
- Hemorrhages
- Exudates
- Blood vessel damage

## 🔍 **Model Implementation**

📜 **File:** AIPRCL_003_Retinopathy.ipynb

🛠️ **Steps Followed:**
- 🧹 **Data Preprocessing** – Image resizing, normalization, and label encoding
- 📊 **EDA (Exploratory Data Analysis)** – Class imbalance check, image samples
- 🧠 **Model Building** – A CNN model for multi-class classification
- 🎯 **Model Evaluation** – Accuracy, confusion matrix, classification metrics
- 🔎 **Prediction** – Predicting DR stage from new/unseen images

## 🤖 **Deep Learning Architecture**

- 📦 Convolutional Layers for feature extraction
- 🌀 Max Pooling for dimensionality reduction
- 🧮 Dense Layers for classification
- 💧 Dropout to prevent overfitting
- 🧠 Softmax for multi-class probability output

## 📉 **Metrics Used**

- 📌 Accuracy
- 📌 Loss
- 📌 Confusion Matrix
- 📌 Precision, Recall, F1-Score

## 🧪 **Technologies Used**

- TensorFlow / Keras
- NumPy & Pandas
- Matplotlib & Seaborn
- OpenCV
- Jupyter Notebook

## 🔑 **Key Insights**

- 👁️ Model can detect various DR stages with good precision.
- 🔁 Data augmentation improved performance on imbalanced classes.
- ⚙️ Preprocessing was crucial to handle image quality variations.

## 🎯 **Conclusion**

This project demonstrates how deep learning can support early diabetic retinopathy screening. With further tuning and validation, the model can be integrated into clinical tools for mass screening and early intervention.

---
