# Task 04 – Hand Gesture Recognition using CNN  
**Internship Track:** Machine Learning  
**Organization:** Prodigy InfoTech  
**Intern:** Rushikesh Kande  

---

## 📌 Objective

Develop a Convolutional Neural Network (CNN) model capable of recognizing different hand gestures using grayscale image data from the LeapGestRecog dataset.

---

## 📂 Dataset Overview

- **Source:** [LeapGestRecog Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Images:** 40,000+ grayscale images  
- **Classes:** 10 different hand gestures  
- **Structure:** 10 users performing each gesture in separate folders

---

## 🧠 Model Architecture

- Convolutional Layers with ReLU activation  
- MaxPooling for spatial reduction  
- Flattening followed by Dense layers  
- Dropout for regularization  
- Final Softmax output for classification

---

## 🧪 Training Details

- **Input Size:** 64x64 grayscale  
- **Optimizer:** Adam  
- **Loss:** Categorical Crossentropy  
- **Epochs:** 10  
- **Batch Size:** 64  
- **Validation Split:** 10%  
- **Test Accuracy:** ~XX% *(replace with your actual value)*

---

## 🚀 How to Run

1. Download the LeapGestRecog dataset from Kaggle  
2. Upload it to your Google Drive and extract it in Colab  
3. Run the notebook below to preprocess data and train the model

Notebook: `PRODIGY_ML_04_Hand_Gesture_Recognition.ipynb`

---

## 🛠️ Dependencies

- TensorFlow  
- NumPy  
- OpenCV  
- scikit-learn  
- matplotlib

---

## 📬 Output

- Trained gesture classification CNN model  
- Evaluation metrics on test dataset  
- Training and validation accuracy during learning

---

## 🌟 Result

The model successfully classifies hand gestures with strong accuracy, demonstrating the power of CNNs in computer vision tasks like sign language, gesture control, and interactive AI.

