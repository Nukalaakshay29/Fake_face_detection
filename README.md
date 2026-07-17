# Deepfake Face Detection using Deep Learning

## 📌 Overview

This project detects whether a face image is **Real** or **Deepfake (Fake)** using Deep Learning. The model utilizes **FaceNet** for facial feature extraction and **PyTorch** for training a deep neural network capable of identifying manipulated facial images.

---

## 🎯 Objective

To develop an AI-based system that automatically detects deepfake images and helps prevent the spread of manipulated digital media.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- PyTorch
- TorchVision
- FaceNet-PyTorch
- OpenCV
- NumPy
- Pillow
- KaggleHub
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

**Dataset Source:**
- FaceForensics++ (FF++)

The dataset is **not included in this repository** because of its large size. It is automatically downloaded in **Google Colab** using **KaggleHub**.

The dataset contains:
- Real face images
- Deepfake (Fake) face images

Images are preprocessed before training to improve model performance.

---

## ⚙️ Project Workflow

1. Download the FaceForensics++ dataset using KaggleHub.
2. Preprocess face images.
3. Extract facial embeddings using FaceNet.
4. Split the dataset into training and testing sets.
5. Train a PyTorch deep learning model.
6. Evaluate model performance.
7. Predict whether an input face is Real or Fake.

---

## 📁 Project Structure

```
Fake_face_detection/
│
├── face_detection.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Fake_face_detection.git
```

2. Move into the project folder.

```bash
cd Fake_face_detection
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Open the notebook in **Google Colab** or **Jupyter Notebook**.

5. Run the notebook cells. The FaceForensics++ dataset will be downloaded automatically using **KaggleHub**.

---

## 📊 Features

- Deepfake face detection
- Automatic dataset download using KaggleHub
- Face preprocessing
- Face embedding extraction using FaceNet
- Deep learning classification using PyTorch
- Model training and evaluation
- Real vs Fake prediction

---

## 📈 Future Improvements

- Train on larger deepfake datasets.
- Improve model accuracy using Vision Transformers (ViT).
- Deploy the model as a Flask web application.
- Develop a browser extension for fake media detection.
- Add support for deepfake video detection.

---

## 👨‍💻 Author

**Nukala Akshay**

B.Tech Computer Science and Engineering (Cyber Security)

---

## ⭐ If you found this project useful, consider giving it a star!
