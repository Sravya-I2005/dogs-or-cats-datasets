# 🐶🐱 Cats vs Dogs Classification using SVM

## 📌 Overview

This project uses a **Support Vector Machine (SVM)** to classify images of cats and dogs.

## 🎯 Objective

Build a basic image classifier using traditional machine learning techniques.

---

## 📂 Project Structure

```
dataset/
   cats/
   dogs/

svm_cats_dogs.py
README.md
```

---

## ⚙️ Installation

```bash
pip install numpy opencv-python scikit-learn
```

---

## ▶️ Usage

```bash
python svm_cats_dogs.py
```

---

## 🧠 Methodology

1. Load images from dataset
2. Resize images to fixed size (64x64)
3. Convert to grayscale
4. Flatten images into vectors
5. Train SVM classifier
6. Evaluate accuracy

---

## 📊 Model Details

* Algorithm: Support Vector Machine (SVM)
* Kernel: Linear
* Input: Flattened image pixels

---

## 📈 Output

* Classification accuracy printed in console

---

## ⚠️ Limitations

* Low accuracy compared to deep learning
* Cannot capture spatial features effectively

---

## 🔮 Future Improvements

* Use CNN (TensorFlow / PyTorch)
* Data augmentation
* Hyperparameter tuning (RBF kernel)
* Feature extraction (HOG, PCA)

---

## 📜 License

Free to use for learning purposes.
