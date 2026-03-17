# traffic-sign-classification-cnn
CNN model to classify traffic signs with ~99% accuracy using TensorFlow
# 🚀 Traffic Sign Classification using CNN

## 📌 Overview

This project focuses on building a deep learning model using Convolutional Neural Networks (CNN) to classify traffic signs into 43 different categories. The model is trained on a large dataset of traffic sign images and achieves high accuracy.

---

## 📂 Dataset Information

* Dataset: German Traffic Sign Recognition Benchmark (GTSRB)
* Total Images: ~78,000
* Number of Classes: 43
* Image Size: 32 × 32 pixels
* Data Split:

  * Training: 80%
  * Validation: 20%

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## 🧠 Model Architecture

The CNN model consists of:

* Convolutional Layers (Conv2D)
* MaxPooling Layers
* Flatten Layer
* Fully Connected Dense Layers
* Dropout Layer (to prevent overfitting)
* Output Layer (Softmax activation for 43 classes)

---

## 🚀 Workflow

1. Data Loading from directories
2. Image Preprocessing (Resizing & Normalization)
3. Train-Validation Split
4. CNN Model Building
5. Model Training
6. Model Evaluation
7. Visualization (Accuracy Graph)
8. Confusion Matrix & Classification Report
9. Prediction on New Images

---

## 📊 Results

* Training Accuracy: ~99%
* Validation Accuracy: ~99%
* Low loss and high model stability

---

## 📈 Model Evaluation

* Accuracy vs Validation Accuracy Graph
* Confusion Matrix for performance analysis
* Classification Report (Precision, Recall, F1-score)

---

## 🔍 Sample Prediction

The model successfully predicts traffic sign classes from unseen images.

---

## 📌 Conclusion

The CNN model achieved excellent performance in classifying traffic signs and demonstrates strong generalization ability. This project can be extended for real-time traffic sign detection systems in autonomous driving.

---

## 🔗 Author

**Ajith M**
Aspiring AI/ML Engineer
GitHub: Ajith-M-Ai
