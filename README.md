# 🧠 Neural Network and Deep Learning Projects

This repository contains projects and assignments from the *Neural Networks & Deep Learning* course, applying CNNs and transfer learning across medical and audio domains, alongside hands-on implementation of core deep learning concepts.

---

## 📌 Projects Summary

### 🔬 Dog Heart VHS Detection  
📂 [`project2/`](./project2/)  
- Used transfer learning (InceptionV3) to predict vertebral heart size (VHS) from canine X-rays.  
- Achieved **86.3% accuracy** and **MSE ≈ 0.208** for keypoint regression.  
- 📄 [ResearchGate Paper](https://www.researchgate.net/publication/386541035_Vertebral_Heart_Score_Prediction_Using_Deep_Learning_for_Canine_Cardiomegaly)

### 💓 Cardiomegaly Classification (DogHeartCNN)  
📂 [`project3/`](./project3/)  
- Built a custom CNN to detect enlarged hearts in canine X-rays.  
- Reached **~73% validation accuracy**; trained and evaluated on 1,600 radiographs.  
- Included model tuning, confusion matrix, and PDF report write-up.

### 🎵 Music Genre Classification  
📂 [`Final_project/`](./Final_project/)  
- Trained a 1D CNN using MFCCs and spectral features from audio to classify 10 genres.  
- Achieved **~77% test accuracy** using the GTZAN dataset.  
- 📄 [ResearchGate Paper](https://www.researchgate.net/publication/387290921_A_Novel_CNN_Architecture_for_Music_Genre_Classification_from_Audio_Features)

### 🌱 Project 1: Neural Network Basics  
📄 [`project_one_AndriaGraceFNU.ipynb`](./project_one_AndriaGraceFNU.ipynb)  
- Built a foundational neural network from scratch for a basic classification task.  
- Practiced forward/backward propagation and activation functions using TensorFlow.

---

## 🧪 Homework Assignments  
📂 [`Homework_Week2` → `Homework_Week7`](./)  
- **Topics Covered:**  
  - Neural network implementation  
  - MLPs & backpropagation  
  - Activation functions  
  - CNN fundamentals  
  - Model evaluation  
  - End-to-end model development  
- Each week includes code notebooks and outputs for reinforcement of core DL concepts.

---

## 🧰 Tools & Technologies

- **Languages:** Python  
- **Libraries:** TensorFlow, Keras, Librosa, OpenCV, NumPy, Pandas, Matplotlib, Seaborn  
- **Concepts:** Transfer Learning, CNNs, Regression, 1D Audio CNNs, Evaluation Metrics, MFCCs, Dropout, Custom Architectures

---

_This repository highlights practical implementations of deep learning across healthcare, audio, and computer vision applications._
