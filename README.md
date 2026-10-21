# 🚢 Titanic Survival Prediction with Neural Networks

An introductory Machine Learning & Deep Learning project predicting passenger survival on the Titanic dataset using modern TensorFlow/Keras and Pandas pipelines.

## 📌 Overview
This project demonstrates end-to-end processing of tabular data and building a 3-layer fully connected Neural Network (DNN) classifier.

## 🛠 Tech Stack
- **Python 3.9+**
- **Pandas & NumPy** (Data Preprocessing & One-Hot Encoding)
- **Keras** (Deep Neural Network)
- **Scikit-Learn**

## 📊 Pipeline Architecture
1. **Data Preprocessing**:
   - Column removal (`name`, `ticket`)
   - Categorical feature encoding (`sex` → binary float)
   - One-Hot Encoding for classification labels (`[1, 0]` vs `[0, 1]`)
2. **Neural Network Model**:
   - **Input Layer**: 6 features (`pclass`, `sex`, `age`, `sibsp`, `parch`, `fare`)
   - **Hidden Layers**: 2 Dense layers with 32 neurons each
   - **Output Layer**: Dense layer with 2 outputs (Softmax activation)
3. **Training & Inference**:
   - Trained with `Adam` optimizer & `Categorical Crossentropy` loss over 20 epochs
   - Achieved ~78-80% accuracy on training iterations.

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/projects-from-matik/titanic-survival-prediction.git](https://github.com/projects-from-matik/titanic-survival-prediction.git)
   cd titanic-survival-prediction
