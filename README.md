# Soft-Tissue-Tumor-Detection-ML
Automated tumor classification system using CNN and image processing
#  Tumor Detection Web Application using CNN & Flask

A complete machine learning project that trains a Convolutional Neural Network (CNN) to detect soft tissue tumors as benign or malignant, and deploys it through a Flask-based web interface.

---

## 🚀 Project Overview

This project demonstrates the end-to-end pipeline of an AI system — from model training using image data to real-time prediction on a web platform. Users can register, log in, upload MRI scan filenames, and receive predictions with confidence scores.

---

##  Workflow

### 🔹 Phase 1 – Model Training (`cnn.py`)
- Preprocessed tumor images using OpenCV and resized them to 50×50 pixels.
- Labeled data based on filenames (`b` = benign, `m` = malignant).
- Built a CNN using TFLearn with 5 convolution layers, dropout, and softmax output.
- Trained for 100 epochs and saved the model.
- Accuracy achieved: **~85%**

### 🔹 Phase 2 – Web App Prediction (`app.py`)
- Flask-based app with HTML templates for login, upload, and result display.
- SQLite database used to register and validate user credentials.
- Accepts image filenames, loads the image, and preprocesses it for prediction.
- Loads the saved CNN model and shows predicted result (benign/malignant) with accuracy.

---

##  Technologies Used

- **Python**  
- **Flask** (Web Framework)  
- **OpenCV** (Image Preprocessing)  
- **TFLearn** (CNN model on TensorFlow)  
- **SQLite** (User data storage)  
- **HTML/CSS** (Frontend templates)

---

## 📁 Project Structure
## 📂 Model File Note

Due to size limits, model files may not be uploaded here.  
👉 Download the trained model from: [https://drive.google.com/file/d/1RPRFkfu8swTEjYu5UcLmpvr8Ze_4_Tnw/view?usp=sharing]



