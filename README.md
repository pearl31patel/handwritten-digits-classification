# handwritten-digits-classification
A deep learning project that classifies handwritten digits (0–9) using the MNIST dataset and a fully-connected neural network built with **TensorFlow & Keras**.

This project demonstrates the complete machine learning pipeline: data loading, preprocessing, model building, training, evaluation, and visualization.

---

## 📌 Project Overview

Handwritten digit recognition is a fundamental computer vision problem.  
In this project, we train a neural network to recognize digits written by humans with high accuracy.

The model learns patterns from thousands of digit images and predicts the correct label for unseen inputs.

---

## 🧠 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🗂️ Dataset

- **MNIST Dataset**
- 60,000 training images  
- 10,000 testing images  
- Each image: **28 × 28 grayscale pixels**

---

## ⚙️ Model Architecture

| Layer | Description |
|-----|-----------|
| Input | 28 × 28 image (flattened to 784) |
| Dense | 100 neurons, ReLU |
| Dense | 10 neurons |

**Optimizer:** Adam  
**Loss Function:** Sparse Categorical Crossentropy  
**Metric:** Accuracy  

---

## 📊 Results

| Model | Training Accuracy | Testing Accuracy |
|------|------------------|-----------------|
| Without Hidden Layer | 92.55% | 92.64% |
| With One Hidden Layer | 98.48% | 97.64% |

---

## 🔍 Key Insights
Adding one hidden layer greatly improves how well the model learns and predicts. This shows that deeper neural networks can understand patterns better than simpler models.

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/handwritten-digits-classification.git
cd handwritten-digits-classification
```
## 👤 Author

**Pearl Viralkumar Patel**  
🎓 *Master’s in Computer Engineering*, University of South Florida — **May 2026**  
💼 *Aspiring Software Engineer / Machine Learning Engineer*

📧 **pearl31patelus@gmail.com**


