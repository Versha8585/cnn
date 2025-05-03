# cnn
# 🧠 CNN Image Classification Project

This project implements a Convolutional Neural Network (CNN) for **2D or 3D image classification** using TensorFlow and Keras. The model is trained to classify images into binary categories (0 or 1) based on provided datasets. It includes data preprocessing, model training, evaluation, and model saving functionalities.

---

# 2D CNN Image Classifier 📊🖼️

This project is a Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify 2D grayscale images (size 64x64) into binary classes (0 or 1).

## 📂 Dataset
- Grayscale images: shape (64, 64, 1)
- Labels: 0 or 1

## 📈 Features
- Data Normalization (0-1 scaling)
- 3 Convolutional + MaxPooling Layers
- Dropout Regularization
- Data Augmentation (optional)
- Accuracy & Loss tracking
- Model Saving (`.h5` format)

## 📝 Dependencies
- numpy
- tensorflow
- sklearn

## 🚀 How to Run
1. Upload your `X.npy` and `y.npy`
2. Run the notebook or script
3. Model will be trained, evaluated, and saved as `cnn_2d_image_classifier.h5`

## 📊 Results
- Accuracy: ~70-90% (depends on data quality & balance)
- Loss: Monitored via training & validation plots

---

## 📌 Author
versha (2025)
