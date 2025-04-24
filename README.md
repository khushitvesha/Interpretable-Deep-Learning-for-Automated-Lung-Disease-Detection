# 🫁 Interpretable Deep Learning for Automated Lung Disease Detection

This project applies deep learning techniques to automate the detection of lung diseases from chest X-ray images. The focus is not only on model performance but also on interpretability — helping medical professionals understand what the model is seeing.

---

## 📌 Objective

- Develop a CNN-based model to classify chest X-rays for lung disease detection.
- Visualize and interpret model predictions using techniques like Grad-CAM.
- Support healthcare diagnosis with transparent, explainable AI tools.

---

## 🧾 Dataset

- **Source:** [Chest X-ray dataset (e.g., NIH, Kaggle)](https://www.kaggle.com/datasets/nih-chest-xrays)
- Includes thousands of labeled X-ray images (normal vs. pneumonia and other lung conditions)

---

## 🧠 Model Architecture

- **Convolutional Neural Network (CNN)**
  - Feature extraction from grayscale medical images
- **Transfer Learning** (e.g., ResNet, VGG)
  - Improves performance on limited medical data
- **Grad-CAM / Activation Maps**
  - Makes model decisions explainable to humans

---

## 🔍 Steps Performed

- 📦 **Data Preprocessing**
  - Normalized, resized, and split into train/test sets
- 🧪 **Model Training**
  - CNN + Transfer learning with cross-entropy loss
- 📊 **Evaluation**
  - Accuracy, Precision, Recall, F1 Score
- 🔎 **Interpretability**
  - Grad-CAM heatmaps to visualize learned attention

---

## 💡 Key Findings

- Achieved over **90% accuracy** on validation data
- Grad-CAM clearly highlighted lung regions showing signs of infection
- Model's interpretability made it easier to validate for healthcare use

---

## 🛠️ Tools & Frameworks

- Python
- TensorFlow / Keras
- OpenCV, NumPy, Matplotlib
- Grad-CAM for model visualization

---

## ⚠️ Limitations

- Limited dataset diversity may affect generalization
- Not a substitute for clinical diagnosis — intended to assist professionals
- Interpretability tools improve trust but are not perfect explanations

---

## 🚀 Future Work

- Test on multi-class lung disease classification (e.g., COVID, pneumonia, tuberculosis)
- Integrate with electronic health record (EHR) data
- Deploy via web app or mobile interface for remote diagnostics

---

## 📎 Files

- `Lung_Disease_Detection.ipynb`: Full notebook with code and visualizations
- `README.md`: Project documentation
- `model_output/`: Folder with Grad-CAM images

---

## 📚 References

- [Grad-CAM: Visual Explanations from Deep Networks](https://arxiv.org/abs/1610.02391)
- [NIH Chest X-ray Dataset](https://www.kaggle.com/datasets/nih-chest-xrays)
- TensorFlow and Keras documentation
